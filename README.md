# fish-z-peco

Search the history of the directory you accessed in the past and jump to it using peco.

## Prerequisites

The following tools and plug-ins are required as prerequisites.
- https://github.com/jethrokuan/z
- https://github.com/peco/peco

## Installation

```fish
fisher install karibash/fish-z-peco
```

## Usage

Please bind `peco_select_z_history` to your favorite key.

If you'd like to bind Ctrl+z:

```fish
function fish_user_key_bindings
  bind \cz peco_select_z_history
end
```
