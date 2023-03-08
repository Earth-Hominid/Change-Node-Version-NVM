# Change-Node-Version-NVM
Change the version of Node using NVM. 

First, install NVM:

```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
```

Second, load it:

```shell
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

Install node version:

```shell
nvm install <node version>
```

Generate a list of node versions:

```shell
nvm ls-remote
```

Use specific node version:
```shell
nvm use <node version>
```

Uninstall
```shell
nvm uninstall <version number>
```
