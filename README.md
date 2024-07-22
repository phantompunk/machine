# Machine
> Inspired by [Thoughtbot/Laptop](https://github.com/thoughtbot/laptop). 

Machine is a simple script to setup a macOS or Linux machine for development.

## Install

For fresh macOS installs run:
```bash
sudo softwareupdate -i -a
xcode-select --install
```

Clone the repo:

```bash
git clone https://github.com/phantompunk/machine.git
```

| 🚧 Use at your own risk! Review and modify before executing. |
| ----------------------------------------------------------- |

Review the script before modifying or executing:

```bash
less machine
```

Execute the downloaded script:

```bash
sh machine 2>&1 | tee ~/machine.log
```

Optionally, review the log:

```bash
less ~/machine.log
```

[Create a SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key)
[Create a GPG Key](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key#generating-a-gpg-key)

## What the script does:

Install Fish Shell as default shell.

Installs Homebrew (package manager for macOS).

Installs developer tools:

- [bat](https://github.com/sharkdp/bat) for a modern replacement for `cat`
- [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) for easier to read git diffs
- [eza](https://github.com/eza-community/eza) for a modern replacement for `ls`
- [fish](https://github.com/fish-shell/fish-shell) for a minimal batteries included shell
- [jq](https://github.com/stedolan/jq) for JSON file parsing
- [mas](https://github.com/mas-cli/mas) for a Mac App Store CLI
- [neovim](https://github.com/neovim/neovim) for a minimal terminal based editor
- [pipx](https://github.com/pypa/pipx) for easy, safe python app installs
- [pre-commit](https://github.com/pre-commit/pre-commit) for managing git pre-commit hooks
- [ripgrep](https://github.com/BurntSushi/ripgrep) for a faster easier grep
- [tldr](https://github.com/tldr-pages/tldr) for quick CLI cheatsheets
- [yq](https://github.com/mikefarah/yq) for parsing YAML files like [jq](https://github.com/stedolan/jq)

Installs language specific tools:

- asdf
- bpython
- node
- pipx
- terraform

Installs Docker/Kubernetes tools:

- colima
- docker
- helm
- k9s
- kind
- kubernetes-cli
- kubectx
- kubeseal
- minikube

Installs useful tools:

- 1password
- Brave Browser
- Google Drive
- Kitty
- Notunes
- Obsidian
- Rocket
- Typora

