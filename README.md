# &lt;polymer-ipsum&gt;

> Web Component Lorem ipsum using Polymer

## Demo

[Check it live!](http://jordifebrer.github.io/polymer-ipsum)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install polymer-ipsum --save
```

Or [download as ZIP](https://github.com/jordifebrer/polymer-ipsum/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/polymer-ipsum/dist/polymer-ipsum.html">
    ```

3. Start using it!

    ```html
    <polymer-ipsum></polymer-ipsum>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`paragraphs`  | *int*       | null         | Number of paragraphs to display
`chars`       | *int*       | null         | Number of characters to display
`reverse`     | *boolean*   | false        | Reverse characters

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/jordifebrer/polymer-ipsum/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
