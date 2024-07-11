# Machine
*Inspired by [thoughtbot/laptop](Thoughbot/Laptop) repo.*

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

- bat
- diff-so-fancy
- eza
- fish
- jq
- mas
- neovim
- pipx
- pre-commit
- ripgrep
- tldr
- yq

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

