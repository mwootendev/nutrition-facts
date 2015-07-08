# &lt;nutrition-facts&gt;

> Nutrition label

## Demo

[Check it live!](http://mwooten.github.io/nutrition-facts)

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

## Options

Attribute        | Options     | Default      | Description
---              | ---         | ---          | ---
`serving-size`   | *string*    | `none`       | The amount in each individual serving.
`servings`       | *string*    | `none`       | The number of servings.
`calories`       | *number*    | `0`          | The number of calories of the product.
`total-fat`      | *number*    | `0`          | The total amount of fat per serving (in grams).
`saturated-fat`  | *number*    | `0`          | The total amount of saturated fat per serving (in grams).
`trans-fat`      | *number*    | `0`          | The total amount of trans fat per serving (in grams).
`cholesterol`    | *number*    | `0`          | The total amount of cholesterol per serving (in milligrams).
`sodium`         | *number*    | `0`          | The total amount of sodium per serving (in milligrams).
`carbohydrates`  | *number*    | `0`          | The total number of carbohydrates per serving (in grams).
`fiber`          | *number*    | `0`          | The total amount of fiber per serving (in grams).
`sugars`         | *number*    | `0`          | The total amount of sugar per serving (in grams).
`protein`        | *number*    | `0`          | The total amount of protein per serving (in grams).

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---

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
