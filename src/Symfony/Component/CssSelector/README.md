CssSelector Component
=====================

CssSelector converts CSS selectors to XPath expressions.

The component only goal is to convert CSS selectors to their XPath
equivalents:

    use Symfony\Component\CssSelector\CssSelector;

    print CssSelector::toXPath('div.item > h4 > a');

Resources
---------

This component is a port of the Python lxml library, which is copyright Infrae
and distributed under the BSD license.

Current code is a port of http://codespeak.net/svn/lxml/trunk/src/lxml/cssselect.py@71545

You can run the unit tests with the following command:

    phpunit -c src/Symfony/Component/CssSelector/
