# Zoho_ZeptoMail for Magento 2

## How to install & upgrade Zoho_ZeptoMail

### 1. Install via composer (recommend)

We recommend you to install Zoho_ZeptoMail module via composer. It is easy to install, update and maintaince.

Run the following command in Magento 2 root folder.

#### 1.1 Install

```
composer require zohomail/magetno-zepto
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### 1.2 Upgrade

```
composer update zohomail/magetno-zepto
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run compile if your store in Product mode:

```
php bin/magento setup:di:compile
```

### 2. Copy and paste

If you don't want to install via composer, you can use this way.

- Download the latest version
- Extract `.zip` file to `app/code/Zoho/ZeptoMail` ; You should create a folder path `app/code/Zoho/ZeptoMail` if not exist.
- Go to Magento root folder and run upgrade command line to install `Zoho_ZeptoMail`:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
