# Machine
*Inspired by [thoughtbot/laptop](Thoughbot/Laptop) repo.*

Machine is a simple script to setup a macOS or Linux machine for development.

## Install

Download the script:

```bash
curl --remote-name https://raw.githubusercontent.com/phantompunk/machine/setup
```

| 🚧 Use at your own risk! Review and modify before executing. |
| ----------------------------------------------------------- |

Review the script before modifying or executing:

```bash
less setup
```

Execute the downloaded script:

```bash
sh setup 2>&1 | tee ~/machine.log
```

Optionally, review the log:

```bash
less ~/machine.log
```

## What the script does:

Install Fish Shell as default shell.
Installs Homebrew (package manager for macOS).
Installs developer tools:

- bat
- diff-so-fancy
- eza
- fish
- jq
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

Installs Kubernetes tools:

- helm
- k9s
- kind
- kubernetes-cli
- kubectx
- kubeseal
- kubeval
- minikube

Installs useful tools:

- Obsidian
- Arc Browser
- Brave Browser
- 

Installs essential developer tools (list customizable in the script).
Sets Fish as the default shell.

brew "asdf"
brew "bat"
brew "bpython"
brew "diff-so-fancy"
brew "eksctl"
brew "eza"
brew "exercism"
brew "fish"
brew "helm"
brew "hugo"
brew "jq"
brew "k9s"
brew "kind"
brew "kubernetes-cli"
brew "kubectx"
brew "kubeseal"
brew "kubeval"
brew "minikube"
brew "mysql-client"
brew "neovim"
brew "node"
brew "pipx"
brew "postgresql@14"
brew "pre-commit"
brew "ripgrep"
brew "terraform"
brew "tldr"
brew "yq"
