# base16-fzf

This repository provides [base16][1] color schemes for [fzf][2], a command-line
fuzzy finder written in Go.

It is meant to be used along with the [new implementation][1] of the base16
color scheme project, which proposes a modular approach by separating templates,
schemes and builder into different repositories.

Themes in base16-fzf work by appending `--color` options to your existing
`FZF_DEFAULT_OPTS` environment variable.

## Installation

Clone the repository:

```text
git clone https://github.com/freddiehaddad/base16-fzf ~/.config/base16-fzf
```

Copy the hook to the base16 shell hook directory:

```text
cp ~/.config/base16-fzf/hooks/10_fzf.sh ~/.config/base16-shell/hooks
```

(Re)apply your base16-shell theme to update fzf.

```text
base16_tokyo-night-dark
```

## Other

This themes were built with [base16-builder-go][3].

[1]: https://github.com/tinted-theming/home
[2]: https://github.com/junegunn/fzf
[3]: https://github.com/tinted-theming/base16-builder-go
