What is Entity Metadata?

Metadata means:

"Data about data"

Entity Metadata is:

Additional information that describes an entity, its fields, behavior, UI representation, permissions, and business rules.





**Example without Meta data**

entity:
  name: Material

  fields:
    name:
      type: string

**Example with Meta data**

entity:
  name: Material

  metadata:
    displayName: "Material"
    icon: "inventory"
    module: "Inventory"

  fields:
    name:
      type: string
