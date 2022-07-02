# Strapi plugin import-export-content LTS

LTS for the Strapi V3 plugin to import and export content according to user permissions in json or csv format.
Orginally authored by [@EdisonPeM](https://github.com/EdisonPeM/) https://www.npmjs.com/package/strapi-plugin-content-type-builder

## Installation

```bash
yarn add strapi-plugin-import-export-content-lts
```

or

```bash
npm i strapi-plugin-import-export-content-lts
```

## Rebuild your administration panel

New releases can introduce changes to the administration panel that require a rebuild. Rebuild the admin panel with one of the following commands:

```bash
yarn build --clean
```

or

```bash
npm run build -- --clean
```

## Features

### Import

- Read data from CSV and JSON file or from typing raw text
- Import contents to collection or single Type
- Manual mapping from source fields to destination fields
- Recognize format of inputs and content types
- Import content as draft or public
- Upload media from URL
- Import Media by id or object with id key
- Import Relations by id or object with id key
- Import Components and Dynamic Zone Content as json objects

### Export

- Export CSV and JSON contents allowed for the user
- Download files or copy exported data to clipboard
- Options to remove ids and timestamps
- Options to export media as ids, urls, full content or full content without formats
- Options to export relatons as ids or full content


## Acknowledgments

This plugin has been inspired by the tutorial [How to create an import content plugin](https://strapi.io/blog/how-to-create-an-import-content-plugin-part-1-4)
