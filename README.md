# fetch_and_paste
Fetch a field from a node or entity, and paste its contents into the current form field.

# So far this is a stub

Envisioned here is a module that will provide a means to fill out a single- or milti-line text field with data taken from another node or entity. This method of reference differs from a direct node or entity reference in that the data loaded into the present field becomes static data of its own, NOT subject to future revision of its parent source of data. This is particularly desireable in the case, for instance, of entering a ship-to or bill-to address of a client as entered into a document such as a purchase order or sales order which must maintain its own static persistence (or permanence) for historical reasons.

In this use case, we wish to provide the user with the ease of quickly and accurately looking up the CURRENT, valid data for the field at hand, without requiring them to type it all in from scratch, or to manually copy-and-paste from, say, a separate lookup window.

In short, the workflow is: 
1. Fetch the currently valid data from a select list, and
2. Paste it as static data into the current field.

## How It Should Work

This module would present a field type of "fetch_and_paste" which, in its definition in the "Add Field" would take the following parameters:
- Source Node or Entity Type
- Specific field, from said source, to copy
- It would be great to duplicate the current functionality of the "node_reference" or "entity_reference" modules with respect to their ability to utilize a filtered view of said source nodes or entities.

I believe that my approach would be to use the code of one of the aforementioned modules as a basis upon which to develop this module.

This envisioned module does not yet exist. I will be working on it as time and resources permit. Any and all contributors who might have the same need are more than welcome to contribute to this effort!

—Cheers,
Eric
