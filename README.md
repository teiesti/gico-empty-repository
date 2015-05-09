# gico-empty-repository
You're looking at an empty repository for the [**G**it based **I**nstaller and **C**onfiguration **O**rganiser](https://github.com/teiesti/gico). Clone this repository to create Your own environment or use `gico init`.

A **gico** repository consists of the following parts:
  - `/hooks/` - a folder that stores hook scripts that will be executed after **gico** completed the resource file installation. Make sure that any script is executable, 
  - `/res/` - a folder that stores all the resources that will be hardlinked to the root directory of Your file system and
  - `/preferences` - a configuration file that specifies which packages should be installed, removed or purged.
