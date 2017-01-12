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

<a href="http://www.youtube.com/watch?feature=player_embedded&v=oN67ZdLat7Q" target="_blank">
	<img src="http://img.youtube.com/vi/oN67ZdLat7Q/0.jpg" alt="Magento 2 UI Component Breakpoints" width="240" height="180" border="10" />
</a>

### Blog Post

There's also a blogpost [here](https://edmondscommerce.github.io/introducing-ui-components/) that goes through this process in much more detail.
