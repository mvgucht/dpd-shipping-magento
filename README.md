Master
======

This branch will hold a copy of each extension update published on magento-connect.

Branches
========

delivery-method-filtered-by-attribute
-------------------------------------

For this addition to work you need to add an attribute to your products.

GOTO Catalog ==> Attributes ==> Manage Attributes
And create a new yes/no-attribute with the attribute code 'delivery_in_parcelshop'

By adding this to your products you can manage a product individually if it can be delivered in a shop or not.

NOTE: When creating the attribute set the default value to 'YES', 
this will ensure that every product you create will be deliverable in a parcelshop by default.

download-labels-as-pdf
----------------------

This alteration joins all labels together in one pdf in stead of joining the pdfs in a zip file.

Requirements
************

Ghostscript installed on server
+ For windows servers: ghostscript folder added to Windows path variable.

checkout-address-limited-input
------------------------------

For this addition to work you need to limit the addresslines to 1.

GOTO System ==> Configuration ==> Customer Configuration ==> Name and address options
And set 'Number of lines in a street address' to 1

export-orders-to-delisprint
---------------------------

This code will add a new action to DPD Orders page/grid.
Files are created in <magentoroot>/var/export/delisprint so you can implement an automated import in delisprint.
