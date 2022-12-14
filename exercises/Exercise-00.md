# Exercise 00

This exercise sets up a new project and the base folder structure.

Create a new project in WebStorm called `Learning-HTML-CSS-JS`.

## Using Command Prompt to Create Folders

Start by opening a Command Prompt session in the terminal by using these steps:

Click on Terminal or use `ALT`+`F12`.

Locate the V or two arrows (depending on your plugins), and click.
![img_3.png](img_3.png)

In the dropdown context menu, click on Command Prompt.
![img_2.png](img_2.png)

> The prompt should show the folder including `Learning-HTML-CSS-JS`.
>
> If your prompt shows PS at the front then you are running PowerShell.
>
> The following commands may not work as expected if you use PowerShell.

Use the command prompt to issue the commands to create the folders:
```shell
mkdir assets
mkdir assets/img
mkdir assets/js assets/css assets/media
mkdir about
```

Now create an empty text file called `.keep` and add to each folder.
- Click on the Project's 'root' folder:
- ![img_4.png](img_4.png)
- This will ensure that the new `.keep` files will be in the correct location.

To create the first copy of `.keep` use `ALT`+`INSERT` and when the pop-up is shown
select `FILE` (If all is well, it will be highlighted by default, so you should
be able to press `ENTER`).
![img_6.png](img_6.png)

Next type in `.keep` and press `ENTER`
![img_5.png](img_5.png)

Now you are able to select the file and press `CTRL`+`C` to copy it to clipboard.

Click on the folder you wish to add a copy to, eg `assets`, and press `CTRL`+`V` to paste it in.

Repeat for the other folders (`assets`, `img`, `css`, `js`, `media`, `about`, etc.)

## Create a ReadMe file

Click on the project root folder.

Use `ALT`+`INSERT` and select `FILE` again

Type in `ReadMe.md` as the filename.

## Create a Cheatsheet File

Click on the project root folder.

Use `ALT`+`INSERT` and select `FILE` again

Type in `CheatSheet.md` as the filename.


## Initialising Git Repo

Click on VCS and then `Enable Version Control Integration`.

![img_7.png](img_7.png)

Select Git and click OK

![img_8.png](img_8.png)

Version Control is initialised.

## Enable PlantUML and Mermaid Syntax

Open settings in WebStorm using `CTRL`+`ALT`+`S` (`CMD`+`,` on Mac)

In the search type in Plant, then navigate to the settings as shown:

![img_9.png](img_9.png)

Click on Install for PlantUML and Mermaid UML support

Then tick either or both to select them

Click OK to apply the settings changes.


## Plugins for WebStorm

Open the settings (see above)

Click on "Plugins"

Click on "Marketplace"

In the marketplace search box search for and install the following:

- .ignore
- CSV
- Rainbow Brackets
- Indent Rainbow
- JSON Helper
- Markdown Editor
- Paste Images into Markdown
- Zero Width Character locator
- Yet another emoji support
- GitToolBox
- Extra ToolWindow Colorful Icons
- Atom Material Icons
- .env files support

You may need to restart the IDE after making plugin changes and/or updates.