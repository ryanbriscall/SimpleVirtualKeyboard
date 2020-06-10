# A simple virtual keyboard

See demo of this as an "Access Panel":

[View Demo](https://ryanbriscall.github.io/SimpleVirtualKeyboard)

Lightweight, compatible, single-page web app (<abbr title="Single-page Application">SPA</abbr>) with no dependencies and zero additional HTTP requests.

Use this for your own authentication (password) page!

## Usage

Simply copy/paste the code from `index.html` into your project.  Customize and minify as you see fit.

## Customize

1. Keys (JavaScript):
   ```js
   var categories = [
      {
         'group': 'a-z',
         'keys': [
               'a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z'
         ]
      },
      {
         'group': 'A-Z',
         'keys': [
               'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'
         ]
      },
      {
         'group': '0-9',
         'keys': [
               '0', '1', '2', '3', '4', '5', '6', '7', '8', '9', '-', '+', '='
         ]
      },
      {
         'group': '!$%',
         'keys': [
               '~', '!', '@', '#', '$', '%', '^', '&', '*', ';', ':', ',', '.', '?'
         ]
      },
      {
         'group': '({[',
         'keys': [
               '(', ')', '{', '}', '[', ']', '<', '>'
         ]
      },
   ];
   ```

## Changelog

### 1.0.0

 - Initial release.

## License

Licensed under the MIT, see the `LICENSE` file for more details.
