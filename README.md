# V3 Demo Importing

This repo holds the contents of the `importing/` path at the root of your Chevereto application. It shows how to provide content to be programmatically imported to Chevereto V3.

## Folder schema

### `no-parse/`

* Import images as guest.
* Any folder structure will be ignored.

### `parse-albums/`

* Top-level folders will be handled as `album_name`.
* Images will belong to `album_name`.

### `parse-users/`

* Top-level folders will be handled as `username`.
* Second-level folders will be parsed as `album_name` belonging to `username`.
* Images will belong to `username`, under `album_name`.

## Documentation

Check the [Bulk Content Importer Documentation](https://v3-docs.chevereto.com/features/bulk-content-importer.html).

## Credits

* [Tony's background](https://dribbble.com/shots/6087096-Scarface-inspired-tropical-wallpaper/attachments/6087096-Scarface-inspired-tropical-wallpaper?mode=media)
* [Bolivia: conoce el encanto de Cochabamba](https://latinamericanpost.com/es/25362-bolivia-conoce-el-encanto-de-cochabamba)
