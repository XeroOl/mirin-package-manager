# Mirin Package Manager
A MacOS/Linux command line tool to make it slightly easier to download plugins for the Mirin Template.
Since Mirin Template plugins don't have any dependencies, this is basically a glorified file downloader. It isn't at all necessary in order to use plugins, as it's only a convenience tool for people who prefer the command line over a web browser.

# Installation (MacOS / Linux)
Should work on MacOS or Linux as long as lua is installed into the path. To install, just place the `mirin`
file somewhere on your path. On my system, I use `~/bin/mirin`, but anywhere on the path is fine. Then, you can run the `mirin` command in the terminal.

# Usage
```
mirin <command> <args>
```

Here are the commands that you can use:

* `mirin help`
    * shows the available commands

* `mirin init <dir>`
    * Creates a folder and downloads the latest version of the Mirin Template into the folder

* `mirin install <plugin>`
    * Finds and installs the specified plugin from the [Plugins Repo](https://github.com/XeroOl/notitg-mirin-plugins)
* `mirin remove <plugin>`
    * Deletes the specified plugin from the plugins folder

* `mirin list`
    * lists all the currently installed plugins

* `mirin list available`
    * Lists all of the plugins that can be downloaded with this tool. Note that this tool only looks in the [Plugins Repo](https://github.com/XeroOl/notitg-mirin-plugins) for plugins. If a plugin is from anywhere else, you can still use the plugin, but you can't install it using this command line tool. Instead, just place the file in the plugins folder manually.
