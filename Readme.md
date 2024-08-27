# Custom Columns for SharePoint Lists

The included folders contain various `json` files used in customizing columns in SharePoint lists (i.e. Microsoft Lists).

## Usage

In SharePoint lists, columns correspond to a form input, whether entered by the user or automatically by SharePoint. Each column type is collected into a folder named after the type of field and/or use case that it was applied to.

Each folder contains a `json` file with a corresponding `readme.md` file explaining what the code does. All columns must have a type assigned to them, with equivalent display choice and default values applied.

To create your own column configuration, copy the [example](example) folder and rename it to meet your desired criteria.

## Icons

All icons are from [Fluent 2](https://fluent2.microsoft.design/iconography).

To select an icon, search for one using the list found at the bottom of the [Iconography/Fluent UI Icons](https://developer.microsoft.com/en-us/fluentui#/styles/web/icons) page. Hover over the desired icon to see what Fluent UI uses to reference the icon - apply that name to the desired area in the `json` file.

---

## Available field types

- [Category](Category/Readme.md)
- [Priority](Priority/Readme.md)
- [Single User Column](SingleUserColumn/Readme.md)
- [Status](Status/Readme.md)
- [TaskType](TaskType/Readme.md)
- [TshirtSizing](TshirtSizing/Readme.md)
