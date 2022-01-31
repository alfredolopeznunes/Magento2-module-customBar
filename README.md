# **LeSite Custom Bar**
LeSite Custom bar module in topnav
Magento module that will display a small bar at the top of the page.

Composer Installation
Go to your magento root path

Add this repository to your composer.json https://github.com/alfredolopeznunes/Magento2-module-customBar.git
Run composer
Example:
```
{
    "repositories": [
        {
            "url": "https://github.com/alfredolopeznunes/Magento2-module-customBar.git",
            "type": "git"
        }
    ],
}
```


- Run bin/magento module:enable LeSite_CustomBar

- Run your magento deployment procedure (setup:upgrade, setup:di:compile) Configurtion.

-In Magento admin go to LESITE CUSTOMBAR > General Configuración to Enable or disable the module.

- You must assign a client group for the user (When creating a user your default group is general).

- If the customer changes their group, they must log back in to apply the changes.
