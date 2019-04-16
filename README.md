# Case Converter FCC
This is a prototype of fcc curriculum project to teach how to build, use and publish npm module. This module itself provide methods to covert string to specify case.

## Install
`npm install case_converter_fcc_sample`

## Usage

```javascript
const caseConverter = require('./index');

const str = 'hello free Code Camp!';
console.log(caseConverter.getUpperCase(str)); // HELLO FREE CODE CAMP!
console.log(caseConverter.getLowerCase(str)); // hello free code camp!
console.log(caseConverter.getProperCase(str)); // Hello Free Code Camp!
console.log(caseConverter.getSentenceCase(str)) // Hello free code camp!
```

## License
The MIT License

# How to build npm module
## Create your module (package)
1. Create a directory for your module.
2. In package root directroy, run `npm init`, and follow the instruction to generate `package.json`.
3. Creat a `README.md` file to explain your package.
4. Write your code and export the methods you want user to call.

## Publish
1. Sign up on [npm](https://www.npmjs.com/).
2. run `npm login` or `npm adduser`, follow instruction.
3. run `npm publish` to publish your module to npm.
4. go to [npm](https://www.npmjs.com/) to check your published package!

## Usage
1. run `npm install module_name` to download and install the package.
2. Whenever your need to use the module use `require` to import the module.

## Update
1. If you want to change version number, run `npm version <update_type>`. [see more](https://docs.npmjs.com/updating-your-published-package-version-number)
2. Run `npm publish`.
3. Go to your package page to check the update.
