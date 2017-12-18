# HTML minify plugin for October CMS

</br>

Plugin based on https://github.com/nochso/html-compress-twig

</br>

Currently supported Twig features are:

Tag 
{% htmlcompress %} ... {% endhtmlcompress %}

Function 
{{ htmlcompress('some html') }}

Filter 
{{ content|markdown|htmlcompress }}

</br>

Install plugin and then use it in your templates:

```php
{% htmlcompress %}{% endhtmlcompress %}

{{ htmlcompress('<ul> <li>') }}

{{ '<ul> <li>'|htmlcompress }}
```
