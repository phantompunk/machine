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

- https://github.com/asdf-vm/asdf for a multi-language runtime manager
- [bpython](https://github.com/bpython/bpython) for a fancy Python REPL
- [terraform](https://www.terraform.io/) for managing IaC

Installs Docker/Kubernetes tools:

- [colima](https://github.com/abiosoft/colima) for a minimal container runtimes
- [docker](https://github.com/docker/cli) for managing container images
- [helm](https://github.com/helm/helm) for managing k8s packages
- [k9s](https://github.com/derailed/k9s) for monitoring k8s resources
- [kind](https://github.com/kubernetes-sigs/kind) for testing k8s in docker
- [kubernetes-cli](https://github.com/kubernetes/kubectl) for managing k8s resources
- [kubectx](https://github.com/ahmetb/kubectx) for switching between k8s environments
- [kubeseal](https://github.com/bitnami-labs/sealed-secrets) for encrypting k8s secrets
- [minikube](https://github.com/kubernetes/minikube) for testing k8s

Installs useful tools:

- [1password](https://1password.com/) for a password manager
- [Brave Browser](https://brave.com/download/) for Chrome with extra privacy
- [Google Drive](https://www.google.com/drive/download/) for syncing Google Drive folders
- [Kitty](https://github.com/kovidgoyal/kitty) for GPU based terminal emulator
- [Notunes](https://github.com/tombonez/noTunes) to disable Itunes from launching
- [Obsidian](https://github.com/obsidianmd/obsidian-releases) for note taking editor
- [Rocket](https://matthewpalmer.net/rocket/) for slack-style emoji shortcuts
- [Typora](https://typora.io/) for minimal markdown editor

