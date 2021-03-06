# CDN for Salesforce Lighning Design System 2.4.3
Used for hosting salesforce-lightning-design-system on github for **TESTING** purposes only. Do not us this in production.

## Contents

* assets/
  - styles/
    - salesforce-lightning-design-system.css (regular CSS)
    - salesforce-lightning-design-system-vf.css (scoped CSS for use in Visualforce)
    - salesforce-lightning-design-system-ltng.css (scoped CSS for use in Lightning Components)


## Usage

Simple copy-paste this css on your html or visualforce pages

### Regular minified CSS 

    <link rel="stylesheet" type="text/css" href="https://rawgit.com/allude/SLDS/master/assets/styles/salesforce-lightning-design-system.min.css">


### Scopped minified CSS for Visualforce

    <link rel="stylesheet" type="text/css" href="https://rawgit.com/allude/SLDS/master/assets/styles/salesforce-lightning-design-system-vf.min.css">


### Scopped minified CSS for Lightning Components

    <link rel="stylesheet" type="text/css" href="https://rawgit.com/allude/SLDS/master/assets/styles/salesforce-lightning-design-system-ltng.min.css">

### Importing Salesforce Regular Fonts

    https://rawgit.com/allude/SLDS/master/assets/fonts/webfonts/SalesforceSans-Regular.woff2?raw=true

### Importing Salesforce Light Fonts

    https://rawgit.com/allude/SLDS/master/assets/fonts/webfonts/SalesforceSans-Light.woff2?raw=true

# Lightning Design System 
# Version: 2.4.3 
# Salesforce Lightning Design System

Welcome to the [Salesforce Lightning Design System](https://www.lightningdesignsystem.com) brought to you by [Salesforce UX](https://twitter.com/salesforceux).

* Tailored for building Salesforce apps: Using the Lightning Design System markup and CSS framework results in UIs that reflect the Salesforce Lightning look and feel.
* Continuously updated: As long as you’re using the latest version of the Lightning Design System, your pages are always up to date with Salesforce UI changes.

## Documentation

[Salesforce Lightning Design System web site](https://www.lightningdesignsystem.com)

## Contents

* assets/
  - fonts/ - the Salesforce Sans font
  - icons/ - PNG, SVG and SVG spritemap versions of icons
  - images/ - including spinners
  - styles/
    - salesforce-lightning-design-system.css (regular CSS — which should not be used within a component that already has access to the SLDS CSS within the platform — please use the scoping tool mentioned below)
    - salesforce-lightning-design-system.min.css (minified CSS)
    - (The scoped files for -vf and -ltng have been removed from the download. If you still need a scoped file, a custom scoped file should be built using [the file scoping tool](https://tools.lightningdesignsystem.com/css-customizer))
* design-tokens/dist/ - the Design Tokens, usable in all formats
* scss/ - the Sass source for the Lightning Design System CSS
* swatches/
  - salesforce-lightning-design-system.ase
  - salesforce-lightning-design-system.clr - adobe and ios swatch formats, respectively. See [https://helpx.adobe.com/photoshop/using/customizing-color-pickers-swatches.html](https://helpx.adobe.com/photoshop/using/customizing-color-pickers-swatches.html)

## Licenses

* Source code is licensed under [BSD 3-Clause](https://git.io/sfdc-license)
* All icons and images are licensed under [Creative Commons Attribution-NoDerivatives 4.0](https://github.com/salesforce-ux/licenses/blob/master/LICENSE-icons-images.txt)
* The Salesforce Sans font is licensed under our [font license](https://github.com/salesforce-ux/licenses/blob/master/LICENSE-font.txt)
