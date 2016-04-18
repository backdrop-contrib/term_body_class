This modules allows addition values of taxonomy type fields of an entity as
classes in the body element, on the entity's page. It adds the settings per
field instance, hence you can enable body classes for individual fields per
entity type and not for a field in all entity types.

How it works -
* on the 'taxonomy term reference' field settings form page, a new checkbox is
available that allows adding its values as body classes
* this setting is saved only for this field instance
* on an entity page, before rendering the html, the module will fetch all fields
associated with the entity, which have been enabled as body classes, convert all
their values that are associated with the node to machine names(with hyphens
instead of underscore) and add to the body classes list

Currently available only for nodes.

How to set up -
* for the taxonomy field which you want as body classes, edit the field settings
for the content type
* check 'Add body class'
* save
