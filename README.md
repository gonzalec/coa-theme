# Color of Art [CoA]

An custom UI theme for Sublime Text 3.

The color of modern art is HEX: #A79F94 (RGB:167 159 148), according to creative artist Joshua T. Nimoy. This color is based on an average color was calculated from more than 26,000 images in the MoMA art collection. 

## Design

Based on Soda Theme by Ian Hill (http://buymeasoda.com/),

I only have changed color and some details.

## Installation

CoA theme is designed to work with the latest stable builds of Sublime Text 3 [Sublime Text 3](http://www.sublimetext.com/3).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Color of Art theme via the `Package Control: Install Package` menu item. The CoA Theme package is listed as `Theme - Color of Art` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/gonzalec/coa-theme/ "Theme - Soda"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Soda`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.


### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Coa Dark 3.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Coa Dark 3.sublime-theme"
    }

## Additional Features

### Alternate Tab Styles

Soda Theme ships with two alternate UI tab styles.

By default, a square tab style is used. If you'd prefer to use the original curved tab style, add the following custom setting to your `Settings - User` file:

    "soda_classic_tabs": true

![Soda Tab Styles](http://buymeasoda.github.com/soda-theme/images/features/multiple-tab-styles.png)

### Sidebar Folder Icons

Soda Theme has the ability to use folder icons in the sidebar.

If you'd like to use folder icons in the sidebar instead of the regular arrows, add the following custom setting to your `Settings - User` file:

    "soda_folder_icons": true

![Soda Folder Icons](http://buymeasoda.github.com/soda-theme/images/features/sidebar-folder-icons.png)

### Retina Resolution UI

Soda Theme has been designed to take advantage of retina resolution (high-dpi) displays. Both Soda Light and Soda Dark support retina displays.

![Soda Retina](http://buymeasoda.github.com/soda-theme/images/features/soda-retina.png)

### Theme Customisation

Sublime Text provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Soda Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page.

## Bonus Options

### Syntax Highlighting Colour Schemes

The Soda Light screenshot uses a modified version of Espresso Tutti Colori and the Soda Dark screenshot uses a modified version of Monokai.

If you'd like to use the syntax highlighting schemes shown in the screenshots: 

* Download [colour-schemes.zip](http://buymeasoda.github.com/soda-theme/extras/colour-schemes.zip)
* Unzip and place the extracted `tmtheme` files in the Sublime Text `Packages/User` folder
* Enable the colour scheme via `Preferences -> Color Scheme -> User`

### Code Font

The code font shown in the screenshot is Menlo.

## Development

Please note, Sublime Text dev builds move quickly and changes can occur with the theme API between releases, so there may be occasions where the theme doesn't quite work with a brand new dev release.

While developing the theme, I have documented some [theme challenges and ideas](https://github.com/buymeasoda/soda-theme/wiki/Theme-challenges-and-ideas) encountered along the way.

## License

Soda Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so. 

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Soda Theme" (or a close variant) in the main project title, repo name or Package Control name.