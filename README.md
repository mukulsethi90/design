# design
Collection of all design related work.

### Layout

- [Logo design files](/logo)
- [UI design files](/ui)
- [Marketing](/marketing)
- [Misc design files](/misc)


### Contributing

Different assets will be kept in their own folder (`/ui/add-button/`), where associated assets will be nested in a common parent folder (`/ui/app/add-button/`, `/ui/app/sub-button/`).

To accommodate different preferences with design tools, asset folders should be organised with:

- Master files - These are the original files used to design the asset (`.ai`, `.afdesign`, `.sketch`, `.psd`, `.pxm`, etc.).
- Portable files - These are commonly cross-supported types (`.svg`, `.eps`), they're not meant to be used as a the main file but rather as an alternative way to load up the current work in an alternative editor.
- Reference files - These are the final products (`.png`), so they can be quickly viewed without requiring third party support for any of the other types.

When updating an asset, any files in that folder which were not touched should be renamed to include the prefix `.`, while any that were changed should have that prefix removed.

```
before:
ui/app/add-button
├── .add-button.afdesign
├── add-button.sketch
├── add-button.eps
├── add-button.svg
└── add-button.png

update add-button.afdesign and all supporting files:
ui/app/add-button
├── add-button.afdesign
├── .add-button.sketch
├── add-button.eps
├── add-button.svg
└── add-button.png
```


### Todo

- [ ] Design guidelines
- [ ] Licensing
- [ ] Scripts to simplify contribution process
