# Scopes

Sometimes more advanced filtering options are necessary. This is where scope filters, callback filters and custom filters come in handy.

# Usage

The following query parameter will add the `popular` scope:

```url
{base_url}/users?scope[]=popular
```

# Remove Global Scopes

Global scopes allow you to add constraints to all queries for a given model.
What if we want to remove it ?

The following query parameter will remove the `delivered` global scope:

```url
{base_url}/books?excludeGlobalScopes[]=delivered
```