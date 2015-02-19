# HPSTR Grav Theme

![HPSTR](assets/readme_1.png)

This [Grav](http://getgrav.org) theme is a port of the [Jekyll HPSTR Theme](https://github.com/mmistakes/hpstr-jekyll-theme) developed my [mmistakes](https://mademistakes.com/). 

This started off as a bit of an experiment to see how much time and effort it would take to port a **Jekyll** theme to **Grav**.  Also I wanted to ensure that Grav had all the features and capabilities to pull this off.  It took me 1 full day to complete from start to finish and is 100% feature complete with the original Jekyll version.  I have taken the liberty to modify the file structure to better suite Grav's organization paradigm.

## Skeleton

The theme by itself is not that useful, so please check out the [HPSTR Skeleton Package](https://github.com/getgrav/grav-skeleton-hpstr-site) that is the self-contained repository for a complete HPSTR site which includes: **sample content**, **configuration**, **theme**, **plugins**.

# Installation

Installing the HPSTR theme can be done in one of two ways. Our GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file. 

## GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install hpstr

This will install the HPSTR theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/hpstr`.

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `hpstr`. You can find these files either on [GitHub](https://github.com/getgrav/grav-theme-hpstr) or via [GetGrav.org](http://getgrav.org/downloads/themes).

You should now have all the theme files under

    /your/site/grav/user/themes/hpstr

>> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

# Updating

As development for the HPSTR theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating HPSTR is easy, and can be done through Grav's GPM system, as well as manually.

## GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update hpstr

This command will check your Grav install to see if your HPSTR theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

## Manual Update

Manually updating HPSTR is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/hpstr` directory.
* Downalod the new version of the HPSTR theme from either [GitHub](https://github.com/getgrav/grav-plugin-hpstr) or [GetGrav.org](http://getgrav.org/downloads/themes#extras).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `hpstr`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.

# Setup

If you want to set HPSTR as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: hpstr`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **hpstr** folder.

---

## License

This theme is free and open source software, distributed under the [MIT License](/LICENSE) version 2 or later. So feel free to to modify this theme to suit your needs.
