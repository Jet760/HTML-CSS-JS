# Learning HTML, CSS and JS with Ady

description here....

## Folder Structure
```text
Root -+- index.html
      |
      +- README.md
      |
      +- about -+- index.html
      |
      +- assets -+- js -+-
                 |
                 +- css -+- site.css
                 |
                 +- img -+-
                 |
                 +- media -+-
```

## .gitignore
creat .gitignore with required file patterns.
>Use the plugin .ignore in JetBrains IDEs.
> 
> `CTRL`+`ALT`+`S` (on Windows) to open settings.
> 
> Click the Plugins option (on the left side).
> 
> Click Marketplace.
> 
> In the search box at the top type in a word that 
> may be part of the plugin needed, eg. ignore.
> 
> Locate the option and click INSTALL.
> 
> Click OK when all plugins are installed.
> Sometimes the IDE will need to restart to apply the changes.


## .keep
This file is used to force folders that are "empty" to be committed...

Add to any folder you need to be added to version control but may not be using immediately

Creat it as a New Text file with thr filename `.keep`

## Useful Plugins
- .ignore
- CSV
- Rainbow Brackets
- Indent Rainbow
- JSON Helper
- Markdown Editor
- Paste images into Markdown
- Zero width character locator
- Yet another emoji support
- GitToolBox
- Extra ToolWindow Colorful Icons
- Atom Material Icons
- .env files support
- 

# Useful Commands
### Make Directory/Folder
In DOS command line:
```shell
mkdir folder_name
```

DOS Example:
```shell
mkdir assets assets\img assets\css assets\js assets\media
mkdir about
```

Linux Example:
```shell
mkdir -p assets/{img,css,js,media} about
```