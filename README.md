# 42 SP Header for VSCode

This Unofficial extension provides the 42 header integration in VS Code. with a small adjustment in the header (SP).

```bash
# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    sp-42header                                        :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: aporto <xxxxxx@xxxxxx.xxx>                 +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2013/11/18 13:37:42 by aporto            #+#    #+#              #
#    Updated: 2021/11/05 13:11:04 by aporto           ###   ########sp.org.br  #
#                                                                              #
# **************************************************************************** #
```

## Install

Launch Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and enter
```
ext install 42header
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "42header.username": string,
  "42header.email": string
}
```

fork of [kube](https://github.com/kube/vscode-42header/).

## License

MIT
