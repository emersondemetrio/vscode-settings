### Personal vscode-settings

On macOS, vscode base folder is:

```sh
~/Library/Application Support/Code/User/
```

Location may be different according to distro.

#### To copy the user `settings`, run:

```sh
cp ~/Library/Application\ Support/Code/User/settings.json .
```

#### To copy the user `keybindings`, run:

```sh
cp ~/Library/Application\ Support/Code/User/keybindings.json .
```

#### To (re)generate the list of `extensions`, run:

```sh
code --list-extensions > extensions.txt

# or

cat ~/.vscode/extensions > extensions.txt
```

#### To copy all `snippets`, run:

```sh
cp -r ~/Library/Application\ Support/Code/User/snippets/ .
```
