# github-pr-vsix

Patched github pr vsix binaries for code oss in cloud workstations

## Usage

Run the following command (There is no need to clone this repository).

```
sudo rm -rf /opt/code-oss/extensions/github.vscode-pull-request-github-0.66.2 && \
sudo wget -O /tmp/vscode-pull-request-github-0.66.2.vsix -q https://github.com/rodion-lim-partior/github-pr-vsix/releases/download/v0.66.2/vscode-pull-request-github-0.66.2.vsix && \
sudo code --install-extension /tmp/vscode-pull-request-github-0.66.2.vsix --user-data-dir="/home/user/.vscode/data" --extensions-dir="/home/user/.codeoss-cloudworkstations/extensions/"
```

1. Click on Github extension on the side bar
2. Click on Sign In Button
3. Go to RDP and open https://github.com/login/device on a browser
4. Key in the code that was provided in vs code
5. Authorize every single organization
