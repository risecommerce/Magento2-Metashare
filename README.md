<h3><a target="_blank" href="https://risecommerce.com/">Risecore Technologies Pvt. Ltd.</a></h3>
<a target="_blank" href="https://risecommerce.com/"><img width="100%" height="208" src="https://risecommerce.com/media/wysiwyg/logowithtext.png"></a>

This extension provide preview for Share via WhatsApp, Facebook, Instagram, Twitter, etc.

##Support: 
version - 2.3.*,2.4.*

##How to install Extension

<h4>Method I:</h4>
<p>1. Download the archive file.</p>
<p>2. Unzip the file</p>
<p>3. Create a folder [Magento_Root]/app/code/Risecommerce/MetaSharing</p>
<p>4. Drop/move the unzipped files to directory '[Magento_Root]/app/code/Risecommerce/MetaSharing'</p>

<h4>Method II:</h4>

Using Composer

```
 composer require risecommerce/metasharing
```

<h4>Enable Extension:</h4>

```
 php bin/magento module:enable Risecommerce_MetaSharing
 php bin/magento setup:upgrade
 php bin/magento cache:clean
 php bin/magento setup:static-content:deploy
 php bin/magento cache:flush
```

<h4>Disable Extension:</h4>

```
 php bin/magento module:disable Risecommerce_MetaSharing
 php bin/magento setup:upgrade
 php bin/magento cache:clean
 php bin/magento setup:static-content:deploy
 php bin/magento cache:flush
```
