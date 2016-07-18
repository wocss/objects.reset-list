# Reset list

The `wocss-objects-reset-list` module contains the reset-list `object`.

Install using npm:

```sh
$ npm install --save wocss-objects-reset-list
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
// dependencies imports

@import '~wocss-objects-reset-list';
```

Then simply add the class to remove any styles that were previously set on a list.

```html
<ul class="o-reset-list">
  <!-- here your content -->
</ul>
```

## Dependencies

* [wocss-tools-bem-constructor](https://github.com/wocss/tools.bem-constructor)
