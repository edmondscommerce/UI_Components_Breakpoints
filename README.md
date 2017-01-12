# Magento 2 UI Components Breakpoints

## By [Edmonds Commerce](https://www.edmondscommerce.co.uk)

A set of PHPStorm breakpoints set up for investigation Magento 2 UI Components

### Installation

* `git clone https://github.com/magento/magento2.git`
* `git checkout tags/2.1.1 -b 2.1.1`
* Follow the magento 2 [installation docs](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/dev_install.html).
* Install [PHPStorm](https://www.jetbrains.com/phpstorm/).
* [Install](https://xdebug.org/docs/install) and [configure](https://www.jetbrains.com/help/phpstorm/2016.3/configuring-xdebug.html) xdebug.
* `git clone https://github.com/edmondscommerce/UI_Components_Breakpoints.git`
* Paste the contents of `breakpoints.xml` into your `.idea/workspace.xml`

```xml
<component name="XDebuggerManager">
    <breakpoint-manager>
        <!-- Paste contents here -->
    </breakpoint-manager>
    ...
</component>
```

### Video

Coming soon!