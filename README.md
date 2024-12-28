The Last updated (**updated**) module enables the monitoring of whenever a node was last updated.  This information is made available in the Administrative GUI, and can also be optionally exposed within the User GUI via checkboxes in the Administrative GUI.  The visibility of Last updated functionality can be controlled at the Content type level or at the individual Node level.  More comprehensive documentation regarding this module (including possible use cases and implementation examples) is available at:
[https://github.com/backdrop-contrib/updated/wiki](https://github.com/ProfessorGram/updated-1.x-1.0.0/wiki)

## Installation
This module does not require a custom installation workflow.  Simply follow the official Backdrop CMS module installation workflow located at:  
https://backdropcms.org/guide/modules

## Administrative GUI Visibility
Post-installation, the day, date and time of the last node update always appears as a read-only field in the "Authoring information" section of the node edit form.

## User GUI Visibility
Post-installation, whether or not text representing the day, date and time of the last node update appears in the User GUI is controlled via checkboxes located in the "Publishing options" section of the node edit form.  By way of this mechanism, it is possible to selectively expose node update information down to a node-by-node basis.

### By *Content Type*
To control Last updated (updated) visibility for an entire *Content Type*:

Visit:

**Administration > Structure > Content types**

or 

**admin/structure/types**

To see a list of all available Content types.  

**Edit** the *Content type* that you wish to have Last updated functionality activated for, then check the checkbox labeled "" [find out] in the "" [find out] area of the *Content type* edit form.

### By Individual Node
To control Last updated (updated) visibility for an individual node:

Visit:

**Administration > Structure > Content types** [this is wrong]

**admin/structure/types** [this is wrong]

**Edit** the node that you wish to have Last updated functionality activated for, then check the checkbox labeled "" [find out] in the *Publishing options* area of the node edit form.


## Issues
Questions, Bug reports and Feature requests can all be added to the Issue Queue for this module, located at:
https://github.com/backdrop-contrib/updated/issues

## License
This is Free and Open Source (FOSS) software.  Please refer to the LICENSE.txt file for a full discussion the licensing terms of this module.
