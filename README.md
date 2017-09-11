[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/FalconSocial/falconio-clipboard)

Polymer 1 element for extracting data out of forms. Part of Falcon.io - Build Elements bundle.

`<build-clipboard>` enables you to copy text into the host system clipboard.

### Example

    <build-clipboard id="clipboard"></build-clipboard>

    <script>
        // let's copy into clipboard for later pasting around
        this.$.clipboard.copy('copy me please');
    </script>


this is pretty much stolen goods from
https://github.com/feross/clipboard-copy/blob/master/index.js
## Running tests from the command line

When in the `falconio-clipboard` directory, run `polymer test`

## License

MIT License