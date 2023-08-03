# github-pr-vsix

Patched github pr vsix binaries for code oss in cloud workstations

## Usage

```
sudo rm -rf /opt/code-oss/extensions/github.vscode-pull-request-github-0.66.2 && \
sudo wget -O /tmp/vscode-pull-request-github-0.66.2.vsix -q https://github.com/rodion-lim-partior/github-pr-vsix/releases/download/v0.66.2/vscode-pull-request-github-0.66.2.vsix && \
sudo code --install-extension /tmp/vscode-pull-request-github-0.66.2.vsix --user-data-dir="/home/user/.vscode/data" --extensions-dir="/home/user/.codeoss-cloudworkstations/extensions/"
```
