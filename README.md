# API Product RBAC - Extended

This module originated as a form of the builtin devconnect API Product Access module.

This module supplants that module,
providing these extensions and improvements:

* "default" access for an API Product.
  When you add a new API Product, it will be exposed to a specific default set of roles.
  The original module always defaulted to exposing the API Product to "any logged-in developer".
  See [This question on the Apigee Community](https://community.apigee.com/questions/46219/api-product-role-access-default-value.html)

* better administrative form for configuration.
  The form is now a table, with checkboxes arranged in rows.


## Compatibility

You could theoretically use this module along with the original devconnect apiproduct access module, but
it does not make much sense to do so.  If you use this module, you should disable the other module.


## Upgrade

There is no "upgrade" from the existing devconnect apiproduct access
module.  If you have previously used the devconnect apiproduct access
module, there is no automatic migration of settings from that module, to
this one.  You will have to manually reproduce the settings.




