# Magento 2 Customer Portal for Hyva add-on for Business Central
Tinx Customer Portal for Business Central in the Azure cloud. 
Add-on to load Jquery for datatables and filers on the My account page

## License

Commercial
Please contact support@tinx-it.com for a valid repository license

## Installation

Install module with composer

```bash
 composer require tinxit/module-customerportalbc-hyva-magento2
```

## Deployment

To deploy

```bash
  bin/magento setup:upgrade
  bin/magento deploy:mode:set production
```
## Tech Stack

Tabletables are not available voor Apline, therefor we need to use Query 3.7.1

**Jquery** 3.7.1

**DataTables:** 2.1.8

## Documentation

Please contact a Tinx consultant for setup assistance
- Activated the cronjob to retrieve Oauth authorisation key
- Can not be used for BC on premiss installations

## Feedback & support

If you have any feedback, please reach out to us at support@tinx-it.com

## Development team
- [Rene Donkers](https://github.com/LotsofPixels)
- [Jelle Janssens](https://github.com/janssensjelle)
