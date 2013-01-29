# tapitbootstrap Module

The Tapit bootstrap Module is is an extension module to the Tapitbootstrap Theme which is a fork of Base Building Blocks module by [Patricko Coffeyo] (https://github.com/patrickocoffeyo). It allows users to proplerly add blocks, and pages that make full use of Twitter Bootstrap to their Drupal projects without adding Bootstrap into the module.

It ships with a parent module that makes sure Tapitbootstrap Theme is installed and in use (Remember, these modules need Bootstrap!), and a collection of submodules that create completely customizeable Bootstrap Navbars, Administration Menus, standard menus in Bootstrap Dropdown Form, and more.

## Requirements
The Tapitbootstrap Module requires that you use Tapitbootstrap Theme, as it is an extension to that theme.

## Installation
Installation is simple. Make sure that the tapitbootstrap Theme  is enabled and set as default, then enable the tapitbootstrap module. A default set of submodules will be enabled.

## Configuration
All configuration pages are added under admin/appearance/tapitbootstrap. You can customize each submodule (subtabs) there.

## Extension
You can easily write submodules for the tapitbootstrap module, just place it in the submodules folder of the main module.

###Note:
When you write an extension that requires a settings (administration) page, please make sure that the path for that page is "admin/appearance/tapitbootstrap/yourModuleName". Also make sure that the menu item is set to MENU_LOCAL_TASK.

## Contribution
If you find yourself needing to extend tapitbootstrap module (for instance, if you want to build a block that displays a Bootstrap carousel of text/images) then please share it with others!

