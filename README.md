# magento-child-theme
Magento 2.3 Luma Child Theme

## Installation

1. Upload the directory(app/design/frontend/Lucid) files to your Magento 2 project <br />
    `app/design/frontend/{vendorName}`
  
2. Select child theme in admin configuration <br />
    `Content > Design > Configuration`
  
3. Flush the cache <br />
    `php bin/magento cache:flush`
  
4. Deploy the static content <br />
    `php bin/magento setup:static-content:deploy`
