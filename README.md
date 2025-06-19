# Gatsby Remark MakeCode plugin

Renders MakeCode code snippets into images as part of the Gatsby build.

## Adding plugin to Gastby

* add plugin

```
npm install --save gatsby-remark-makecode
```

or

```
yarn add gatsby-remark-makecode
```

* add puppeteer dependency to your project (full or core)

## Configuring the plugin

* add entry in remark section **before** any image processing pluging

```
    "gatsby-remark-makecode",
```

## Using the plugin

In your .md, .mdx files, you can insert JavaScript snippets to be rendered in blocks.

    ```blocks
    let x = 0
    ```

## Development

* install node.js and yarn globally
* build

```
yarn build
```

* watch

```
yarn watch
```

## Skinning

Classes

* ``makecode`` on the container
* ``blocks`` on the image

## Contributing

This project welcomes contributions and suggestions.