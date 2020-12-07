![](https://img.shields.io/github/workflow/status/jakecastelli/trongate-vscode/Node.js%20CI/master?style=flat)
![](https://img.shields.io/visual-studio-marketplace/i/jc-sf.Trongate)
![](https://img.shields.io/visual-studio-marketplace/v/jc-sf.Trongate)
![](https://img.shields.io/visual-studio-marketplace/stars/jc-sf.Trongate)
![][1]

# Trongate Scaffold & Code Snippets

<!-- > Would you like to code faster?  I know I certainly would! 👀️ -->
>This is a Visual Studio Code extension to compliment the Trongate ecosystem.   Consisting of the Trongate framework, Desktop-app and Nitro.  All tirelessly written by David Connelly, who I'd like to make special mention here for his continued dedication and commitment in keeping the web development doors open to everyone.

## Features

### New Trongate Module

Module is the essiential building block in Trongate Framework. However, creating a module from scratch needs you constantly concentrate on creating and naming your folders and files and typing boilerplate code.

<hr>

- Quick Start
  - Make sure you have opened Trongate Project in your workspace, right click on the modules folder for creating a general module or if you want create a sub-module right click on the parent module folder, then select `New Trongate Module`, give a module name.
  - If you want a view template then you will need to give a name for your view file. 

<hr>

* Create a scaffold module on the fly
  * The extension can figure out what you are creating if it is a general module or a sub module, and give you the corresponding code. 
  * With a starter class (default option), complete with api.json in the assets folder ready for you to create whatever is on your mind - enjoy!
  * With a view template, it allows you to name your view file and gives you a starter function `index` to guide you on the road. 
  * now with v1.0.1+ you can create a view, complete with linked CSS and JavaScript files
* Prevent module naming errors
  * The extension will dynamically read your `config.php` and extract the `MODULE_ASSETS_TRIGGER`, if you accidentally name your module the same as the `MODULE_ASSETS_TRIGGER`, the process will terminate and you would be notified. This is a handy feature to avoid a blank screen.

![vsc-101-view](https://user-images.githubusercontent.com/7813262/97399997-6c461400-1942-11eb-91c0-41658b5664ec.gif)


<hr>

### Add PHP and custom Trongate code snippets to speed up your development.

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
| Quick php insert environment variable | `tge` |


![snippets2](https://user-images.githubusercontent.com/7813262/95720453-fd6b8880-0cbc-11eb-9eb7-bf7e170e0090.gif)

* Insert popular frontend frameworks and their elements into your view and template files - akin to the Nitro desktop app developed by David Connelly and can be downloaded at https://www.speedcodingacademy.com/ if you are a member of course.

Use `ctrl+win+alt+/` to bring up the dropdown selector to select your frontend framework
* [Bootstrap 4](https://getbootstrap.com/) > tg:b
* [Defiant](https://defiantcss.com/) > tg:d
* [Materialize](https://materializecss.com/) > tg:ma
* [Milligram](https://milligram.com/) > tg:mi
* [Skeleton](http://getskeleton.com/) > tg:s

#### Table of Nitro Frameworks Inserts > Showing Bootstrap 4 prefixes below:
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
| Password Form | `ctrl+win+alt+p` | `tg:b:password-form`
| Table | `ctrl+win+alt+t` | `tg:b:table`
| TAble Alternative | `ctrl+win+alt+a` | `tg:b:table-alt`
| TEmplate | `ctrl+win+alt+e` | `tg:b:template`

<br>PLEASE NOTE: The `win` key is the same as `super` in Linux and `cmd` on Mac<br><br>

![css](https://user-images.githubusercontent.com/7813262/95720033-6ef70700-0cbc-11eb-98b2-ba4eb908dd48.gif)

## Requirements

You will need the Trongate Framework of course! ❤️

## Why you should use Trongate Framework?
* Imagine a PHP framework that allowed you to build large scale enterprise applications in minutes instead of months.
* Imagine a framework that did NOT get rewritten constantly.
* Imagine a framework that you could learn once and use for a lifetime.
* Imagine a framework that was V1 forever!

## You've just imagined [Trongate](https://trongate.io)


![intro](https://user-images.githubusercontent.com/7813262/95190011-6749e500-081a-11eb-8317-5561a7241e6e.png)


Please report any issues or suggestions on our repo

## Release Notes

### .0.0.1
* Initial release


### 1.0.0
* Added full support akin to the Nitro desktop app
* Dropdown selector and notifications when switched
* See above table for full keyboard shortcuts and prefixes
* Added persistence when frontend framework is chosen
* Added status bar message to remind you which frontend framework is active

### 1.0.1
* dropdown options menu when creating a new module
  * you can choose 'no' (default) to create a class only
  * or choose 'yes' to create a view, with linked CSS and JavaScript files
* added new snippet > tge that will display a dropdown menu of common environment variables
  * BASE_URL, WEBSITE_NAME, OUR_NAME, OUR_TELNUM, OUR_ADDRESS & OUR_EMAIL_ADDRESS

### 1.0.2
* Name your view file when you choose to have a view template
* Sub-module support - the extension can figure out automatically for you whether you are creating a general module or a sub-module
* Prevent module naming errors - if your module name which contains the `MODULE_ASSETS_TRIGGER`, it will stop you and let you know

### 1.0.3
* Small fix to the snippet tgm, tgm1, tgm2, tgm3
* Adjusted the cursor position for snippet tg:submit

[1]:https://img.shields.io/badge/Trongate%20Framework-eco--system-blue?logo=data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAMCAgICAgMCAgIDAwMDBAYEBAQEBAgGBgUGCQgKCgkICQkKDA8MCgsOCwkJDRENDg8QEBEQCgwSExIQEw8QEBD/2wBDAQMDAwQDBAgEBAgQCwkLEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBD/wAARCAAQABADAREAAhEBAxEB/8QAFgABAQEAAAAAAAAAAAAAAAAABQYH/8QAJRAAAQMDBAICAwAAAAAAAAAAAgEDBQQGBwgREiEAMRMUQWFx/8QAGQEAAQUAAAAAAAAAAAAAAAAABQABAgQH/8QAIREAAgEDBAMBAAAAAAAAAAAAAQIRAAMEBQYhMUFRcRL/2gAMAwEAAhEDEQA/ALrRjgTG1yY0lr7zXRRxR9xSDMXCDWGjJIYHtzaNVReRuFwRE98F81vdW5M+3lpY09iCgJaOe/fwc0Ps21iWoHWZpUt/DsXT35YROhEPPpT1FK6XL4yL1sv92/XvpNu7O193ZOoOcfKMt2DTXbKrytFaS8ewN6HE3ZlHKlLRQFoSPzQ0JUSwNr9kTFwlVpxdgbJVFdx7VUXwZree9kNaxbcs4hmjx12PNJR7rcdd1xxl9YfbatHINtVFPGVo1sjRhItG/UgicQFoRVVJUIt1TrpN/wAeBdtI2JlzdQyRAMcD7UnP6Ff/2Q==