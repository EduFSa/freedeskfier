FREEDESKFIER
============================================
This is a simple [NativeFier](https://github.com/nativefier/nativefier) wrapper to be used in FreeDesktop compatible Linux distros to create desktop entries for a single Nativefier call. The script also helps to remove all the web applications you already installed with the script.

## NOTICE
 
- This app still not remove any personal data created by the NativeFier application after uninstalling.
- It creates or uses the folders $HOME/.local/bin and #HOME/.local/lib to install the application. Apps can be called by the shell if the "~/.local/bin" folder is already in PATH enviroment variable. 
- This app still not put categoryzed entries on Application Menus #TODO

## REQUIREMENTS

- [NativeFier](https://github.com/nativefier/nativefier)
- Compatible FreeDesktop Linux desktop enviromen

## USAGE

### Install App

#### BASIC 

```
freedeskfier install -n "Name of Application on Desktop" [nativefier options] 'website.domain'
```

#### ADVANCED
```
freedeskfier install [all nativefier options]
```
Check for additional [NativeFier](https://github.com/nativefier/nativefier) options, check their [API](https://github.com/nativefier/nativefier/blob/master/API.md). 

### List Nativefier apps installed

```
freedeskfier list
```
This will list line by line all the compatible apps's folders in ~/.local/bin .

### Remove Application

```
freedeskfier remove [Application folder]
```



