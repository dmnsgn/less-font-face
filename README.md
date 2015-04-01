# less-font-face
Font-face mixin for less

## Install

```bash
$ npm install less-font-face --save
```

## Usage

```less
@import "../node_modules/less-font-face/_font-face.less";

@font-regular: 'Open Sans Regular';

.font-face(@font-regular, 'fonts/', 'OpenSans-Regular-webfont', 'open_sansregular');

.element {
  font-family: @font-regular;
}

```

## License

MIT
