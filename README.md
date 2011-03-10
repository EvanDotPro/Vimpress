Vimpress
========

## DESCRIPTION

The original Vimpress was created by **Adrien Friggeri** and can be downloaded at [the official vim page](http://www.vim.org/scripts/script.php?script_id=1953)

This is a **Willian Molinari (a.k.a PotHix)** fork to add some new features.


## FEATURES
* Get a list of all articles
* Write a new article
* Edit a current article
* Save (yeah, no kidding)
* Supports categories
* Supports tags1

## COMMANDS
* **:BlogList** Lists all articles in the blog
* **:BlogNew** Opens page to write new article
* **:BlogOpen <id>** Opens the article <id> for edition
* **:BlogSend** Saves the article to the blog
* **:BlogDefault** Define the default blog using the <index> of the config file

## INSTALLATION

Just copy all folders to your .vim folder

## SETTINGS

Edit the custom/configs.vim file to your real settigs.
This is a comma separated line, with this informations:
login, password, URL for your xmlrpc.php file


## LICENSE

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2, or (at your option)
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software Foundation,
Inc., 59 Temple Place - Suite 330, Boston, MA 02111-1307, USA.
