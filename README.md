# Marine Dark Colorscheme

This repository houses **Marine Dark** colorscheme for different terminal emulators like **Alacritty**, **ST (Simple Terminal)** & **.Xresources**

## Usage

#### Alacritty
Copy the contents of `alacritty/marine-dark.yaml` to your alacritty config replacing the old colorscheme. Alacritty config is mostly located in `$HOME/.config/alacritty/` directory.

Alternatively you can include `alacritty/marine-dark.yaml` file in your `$HOME/.config/alacritty/alacritty.yml`

---

#### Xresources
Copy the contents of `xresources/Xresources` to your `.Xresources` file, which is mostly located in your `$HOME` dir & run the following command

```
$ xrdb .Xresources
```
---

#### ST (Simple Terminal)

Clone the **ST** repository if haven't already
```
$ git clone https://git.suckless.org/st
```

Copy `st/st-marine-dark-0.9.diff` to your `ST` folder (or where ever you like) and run the patch command
```
$ patch -p1 < path/to/st-marine-dark-0.9.diff
```
Don't forget to resolve conflicts if any, and build **ST** with
```
$ sudo make install
```

## Note
**Marine Dark** will be compatible with additional terminal emulators soon.

## Checkout
- Marine Dark for [VS Code](https://github.com/MarineDark/marine-dark-vscode)
- Marine Dark [Homepage](https://marinedark.github.io)

## Donate Crypto
- BTC `18Hd1waYh5uG6nWRboXGD3Q3vaPzWRMgQH`
- ETH `0x90b3f1495724e9e6a18372cb939df1d7166337b9`
- XMR `88ZscYwoNmTcf2xM1d6UFuGr2eyNh8V6kU2NkZFC7zTA84fWjjHMxrnDdHrquFm1sFRCvGXejvz2bBfBRZLNE5DQ3fngypz`
