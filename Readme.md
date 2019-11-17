# Bdcrops Magento 2 Theme



## Goal

- Frontend Developer




![](docs/attributeSet.png)


## Theme Development Step By Step Tutorials

- [app/design/frontend/Bdcrops/B2theme/registration.php](registration.php)

    <details><summary>Source</summary>

      ```
      <?php
      use \Magento\Framework\Component\ComponentRegistrar;
      ComponentRegistrar::register(
          ComponentRegistrar::THEME, 'frontend/Bdcrops/b2theme', __DIR__
      );

      ```
    </details>


- Create [app/design/frontend/Bdcrops/B2theme/theme.xml](theme.xml)

  <details><summary>Source</summary>

      ```
        <?xml version="1.0"?>
        <theme xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="urn:magento:framework:Config/etc/theme.xsd">
            <title>Bdcrops B2theme</title>
            <parent>Magento/blank</parent>
            <media> <preview_image/> </media>
        </theme>{
        "name": "bdcrops/theme-frontend-b2theme",
        "description": "N/A",
        "config": {
          "sort-packages": true
        },
        "require": {
          "php": "~7.1.3||~7.2.0||~7.3.0",
          "magento/framework": "102.0.*",
          "magento/theme-frontend-blank": "100.3.*"
        },
        "type": "magento2-theme",
        "license": [
          "OSL-3.0",
          "AFL-3.0"
        ],
        "autoload": {
          "files": [
              "registration.php"
          ]
        },
        "version": "100.3.3"
        }
      ```
  </details>

- Create [app/design/frontend/Bdcrops/B2theme/composer.json](composer.json)

  <details><summary>Source</summary>

      ```
      {
          "name": "bdcrops/theme-frontend-b2theme",
          "description": "N/A",
          "config": {
              "sort-packages": true
          },
          "require": {
              "php": "~7.1.3||~7.2.0||~7.3.0",
              "magento/framework": "102.0.*",
              "magento/theme-frontend-blank": "100.3.*"
          },
          "type": "magento2-theme",
          "license": [
              "OSL-3.0",
              "AFL-3.0"
          ],
          "autoload": {
              "files": [
                  "registration.php"
              ]
          },
          "version": "100.3.3"
      }
      ```
  </details>

## Ref
