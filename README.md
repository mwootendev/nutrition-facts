# &lt;nutrition-facts&gt;
===========
> Nutrition Facts Label

See the [component page](http://mwootendev.github.io/nutrition-facts/) for full
documentation.

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install nutrition-facts --save
```

Or [download as ZIP](https://github.com/mwooten/nutrition-facts/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/nutrition-facts/nutrition-facts.html">
    ```

3. Start using it!

    ```html
    <nutrition-facts serving-size="8 fl oz (240 mL)" servings="2.5" calories="110" total-fat="0" sodium="70" carbohydrates="31" sugars="30"></nutrition-facts>
    ```
## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/nutrition-facts/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/mwooten/nutrition-facts/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
