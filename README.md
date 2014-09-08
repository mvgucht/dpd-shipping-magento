delivery-method-filtered-by-attribute
=====================================

For this addition to work you need to add an attribute to your products.

GOTO Catalog ==> Attributes ==> Manage Attributes
And create a new yes/no-attribute with the attribute code 'delivery_in_parcelshop'

By adding this to your products you can manage a product individually if it can be delivered in a shop or not.

NOTE: When creating the attribute set the default value to 'YES',
this will ensure that every product you create will be deliverable in a parcelshop by default.

UPDATE: For this code to work you need to set the price calculation to tablerate, otherwise the price isn't calculated by added product and parcelshops delivery method will always show.
