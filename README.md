# Trongate Scaffold & Code Snippets

Would you like to code faster?  I know I certainly would! 👀️

This is a Visual Studio Code extension to compliment the Trongate ecosystem.   Consisting of the Trongate framework, Desktop-app and Nitro.  All tirelessly written by David Connelly, who I'd like to make special mention here for his continued dedication and commitment in keeping the web development doors open to everyone.

### TRONGATE is the One-V framework that will make PHP great again!

![Scaffold](https://user-images.githubusercontent.com/7813262/95190011-6749e500-081a-11eb-8317-5561a7241e6e.png)

## Features

This extension will allow you to:

* Create a blank module directory scaffold similar to the Desktop-app but with a starter class and asset.json ready for you to create whatever is on your mind - enjoy!

![scaffold](https://user-images.githubusercontent.com/7813262/95719555-b92bb880-0cbb-11eb-9579-f8a85675226a.gif)

* Add PHP and custom Trongate code snippets to speed up your development.



#### Table of helpful Trongate snippets:
| Snippet Name | Prefix 
| ------------- | ------------- 
| Trongate For Loop In View File | `tg:for` |
| Trongate if condition in View File | `tg:if` | 
| Trongate if else in View File | `tg:ifelse` | 
| Trongate Submit Function Scaffold | `tg:submit` | 
| Create new class the extends Trongate | `tgc` |
| Create new method with or without args | `tgm`, `tgm1`, `tgm2`, `tgm3` |
| Add an acnchor with url | `tga` |
| Insert a Template | `tgt` |
| Add [$data] = '' | `tgde` |
| Add [$data] = $this-> | `tgdl` |
| Quick php insert variable | `tgev` |


![snippets2](https://user-images.githubusercontent.com/7813262/95720453-fd6b8880-0cbc-11eb-9eb7-bf7e170e0090.gif)

* Insert popular frontend frameworks and their elements into your view and template files - akin to the Nitro desktop app developed by David Connelly and can be downloaded at https://www.speedcodingacademy.com/ if you are a member of course.

Use `ctrl+win+alt+/` to bring up the dropdown selector to select your frontend framework
* Bootstrap 4 > tg:b
* Defiant > tg:d
* Materialize > tg:ma
* Milligram > tg:mi
* Skeleton > tg:s

#### Table of Nitro Frameworks Inserts > Showing Bootstrap 4:
| Command | Shortcut | Prefix
| ------------- | ------------- | -------------
| Buttons | `ctrl+win+alt+b` | `tg:b:button`
| BUttons Alternative | `ctrl+win+alt+u` | `tg:b:button-alt`
| Contact Form | `ctrl+win+alt+c` | `tg:b:contact`
| Download URL | `ctrl+win+alt+d` | `tg:b:url`
| Form | `ctrl+win+alt+f` | `tg:b:form`
| Grid | `ctrl+win+alt+g` | `tg:b:grid`
| Info Page | `ctrl+win+alt+i` | `tg:b:info`
| Login Form | `ctrl+win+alt+l` | `tg:b:login`
| Modal | `ctrl+win+alt+m` | `tg:b:modal`
| Password Form | `ctrl+win+alt+p` <hr> `ctrl+cmd+alt+o` (mac) | `tg:b:password-form`
| Table | `ctrl+win+alt+p` | `tg:b:table`
| TAble Alternative | `ctrl+win+alt+a` | `tg:b:table-alt`
| TEmplate | `ctrl+win+alt+e` | `tg:b:template`

PLEASE NOTE: The `win` key is the same as `super` in Linux and `cmd` on Mac

![css](https://user-images.githubusercontent.com/7813262/95720033-6ef70700-0cbc-11eb-98b2-ba4eb908dd48.gif)

## Requirements

You will need the Trongate Framework of course! ❤️

## Known Issues

No known issues to report 👍

## Release Notes

### .001

Initial release

### 1.0.0

* Added full support akin to the Nitro desktop app
    * Dropdown selector and notifications when switched
    * See above table for full keyboard shortcuts and prefixes
    * Added persistence when frontend framework is chosen
    * Added status bar message to remind you which frontend framework is active
