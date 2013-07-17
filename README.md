Pancake-NumberingSystem
=======================

A simple plugin initially developed to explore the new plugin system in PancakeApp.

It's great news that PancakeApp have released a plugin system but no official document is out on how to develop plugins. So I have reverse engineered the codes and come out with this as an experiment. Feel free to add on to this project! :)

Requirements
------------

You need an installed and running licensed PancakeApp v4 beta.

Installation
------------

- Copy the folder, <code>NumberingSystem</code> to <code>./third_party/modules</code>
- Login to PancakeApp and go to Plugins
- Change the invoicing number pattern if required
- Check "Enabled" to enable the plugin
- Save Plugin Settings
- Done!

Try creating an invoice and you will see the new custom invoice number

Variables
---------

{yyyy} - Year in YYYY, 2013
{yy} - Year in YY, 13
{dd} - Day in DD, 29
{d} - Day in D, 9
{mm} - Month in MM, 09
{mmm} - Month in MMM, JAN / APR / DEC
{num} - Original invoice number with no padding, 8
{num2} - Original invoice number with 2 padding, 08
{num2} - Original invoice number with 3 padding, 008
{num2} - Original invoice number with 4 padding, 0008

Developed by Kong Jin Jie @ [Aspire Designs Pte Ltd](http://www.aspiredesigns.com.sg)