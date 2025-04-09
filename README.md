## Magento 2 German Language Pack

This project forked from Mageplaza and will be continuously updated.

## 1. Language Package Process

This is status of German Language Pack, you can see how many percentage of this project has been done.

## 2. How to Install German Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the German language pack via composer is never easier.

**Install German pack**:

```
composer require iconsofthu/magento2-german-language-pack:dev-master
php bin/magento setup:static-content:deploy de_DE
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

**Update  German pack**:

```
composer update iconsofthu/magento2-german-language-pack:dev-master
php bin/magento setup:static-content:deploy de_DE
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)

Or use these keys:

```
Public Key: c7af1bfc9352e9c986637eec85ed53af
Private Key: 17e1b72ea5f0b23e9dbfb1f68dc12b53
```

### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the German language pack
- Step 2: Unzip German pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the German language pack

You can download the language pack from above link

#### Step 2: Unzip German pack

Unzip the German language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip master.zip app/i18n/Iconocoders/
```

Rename folder `magento2-German-language-pack` to `de_DE`.

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)

### ✓ Method #3. Download and install manually (Not recommended)

To download and install German pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/iconsofthu/magento2-german-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/iconsofthu/magento2-german-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `master.zip` into `app/i18n/Iconocoders/de_DE/`

See this screenshot:

![German pack](https://cdn3.mageplaza.com/media/general/language-pack.png)

This language pack code is: **de_DE**

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to Active the German language pack 

Now time to active the German language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 German language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)

## 4. Supported Magento versions

- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x
- Magento v2.3.x

## 6. Notes 

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/iconsofthu/magento2-german-language-pack/issues/new)

## 7. Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Magento Community

## 8. References 

- https://www.mageplaza.com/magento-2-German-language-pack.html
- https://crowdin.com/project/magento-2


