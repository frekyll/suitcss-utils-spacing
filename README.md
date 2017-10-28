# SUIT CSS utilities: spacing

SUIT CSS image utilities

* Read more about [SUIT CSS's design principles](https://github.com/suitcss/suit/).

## Installation

* [npm](http://npmjs.org/): `npm install suitcss-utils-spacing`
* Download: [zip](https://github.com/frekyll/suitcss-utils-spacing/releases/latest)

## Available classes

* `.u-[margin|padding][Top|Right|Bottom|Left][Xs|Sm|Md|Lg|Xl]`

## Usage

```html
<div class="u-paddingSm">
  <h1 class="u-marginBottomXs">Hello, world!</h1>
  <p class="u-marginBottomMd">This is a paragraph.</p>
</div>
```

### Configuration

#### Adjust the spacing scale via CSS variables

```css
:root {
  --spaceXs: 8px;
  --spaceSm: 16px;
  --spaceMd: 32px;
  --spaceLg: 64px;
  --spaceXl: 128px
}
```

Please refer to the README for [SUIT CSS utils](https://github.com/suitcss/utils/)

## Testing

Install [Node](http://nodejs.org) (comes with npm).

```
npm install
```

To generate a build:

```
npm run build
```

To lint code with [postcss-bem-linter](https://github.com/postcss/postcss-bem-linter) and [stylelint](http://stylelint.io/)

```
npm run lint
```

To generate the testing build.

```
npm run build-test
```

To watch the files for making changes to test:

```
npm run watch
```

Basic visual tests are in `test/index.html`.

## Browser support

* Google Chrome
* Opera
* Firefox
* Safari
* Internet Explorer 8+
* Android 4.1+
* iOS 6+
* Windows phone 8.1+
