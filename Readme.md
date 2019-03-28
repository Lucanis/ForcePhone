# Force Phone

This module sets the mobile phone number, the home phone number, both or one of them as required in the customer and address forms.

## Installation

**Since 1.2 need to be installed by Composer**

### Composer

Add it in your main Thelia composer.json file

```
composer require thelia/force-phone-module:~1.2
```

### Manually (only for version < 1.2)

* Copy the module into ```<thelia_root>/local/modules/``` directory and be sure that the name of the module is ForcePhone.
* Activate it in your Thelia administration panel

## Usage

Activate the module and the home phone number becomes required in the customer and address forms.
Go to module configuration to select which phone numbers (home, mobile, both or one of them) should be required.

Affected pages :
- register
- create address
- update address

## Other

Be sure to set proper translations for phone inputs' labels.

You can find translation for the mandatory input in your administration panel:
` Configuration --> Translation --> Modules --> Set the phone input mandatory for the customer --> Core files `

Translation for the second phone input is in:
` Configuration --> Translation --> Thelia core `
