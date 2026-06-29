Overriding Generated (Default) Behavior or UI Schema
This is one of the most important concepts in Low-Code Platforms, ERP Systems, and Internal Developer Platforms (IDPs).

What Does "Overriding" Mean?
When code is automatically generated, the default behavior may not always meet your business requirements.
Overriding means:
Changing or extending the generated behavior or UI without modifying the generator itself.
Simple Analogy
The generator gives you a default house.
🏠 Standard House
- White walls
- 2 bedrooms
- 1 kitchen
You want:
🏠 Custom House
- Blue walls
- 3 bedrooms
- Balcony
You don't rebuild the entire house.

Why Overriding is Needed

Generated applications are usually:

✅ Generic

But businesses often need:

Custom validations
Custom buttons
Different layouts
Extra fields
Custom workflows
Business-specific rules


Types of Overrides

1. UI Override
Change how the generated UI looks.
Default:
field:
 description:
   type: text
Generated:
Single-line Text Input

2. Layout Override

Default:

layout:
  columns: 1

Override:

layout:
  columns: 2

3. Validation Override

Default:

validation:
  required: true

Business rule:

validation:
  required: true
  minLength: 10


4. Visibility Override

Default:

Always show Supplier field.

Override:

visibleIf:
  isPurchased: true
