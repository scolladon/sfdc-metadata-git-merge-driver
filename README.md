# sfdc-metadata-git-merge-driver

Salesforce Metadata Git merge driver

## Getting Started

Works in Unix like system.
Windows is not tested.

### Installing

```
npm install -g sfdc-metadata-git-merge-driver
```

or

```
yarn globally add sfdc-metadata-git-merge-driver
```

## Usage

### Command Line

```
$ smgmd -h

  Usage: smgmd [options]
```

### Module

```
  var smgmd = require('sfdc-metadata-git-merge-driver');

  sgp({
    
  }, console.log);
```

## Built With

* [commander](https://github.com/tj/commander.js/) - The complete solution for node.js command-line interfaces, inspired by Ruby's commander.
* [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.
* [xmlbuilder](https://github.com/oozcitak/xmlbuilder-js) - An XML builder for node.js similar to java-xmlbuilder.

## Versioning

[SemVer](http://semver.org/) is used for versioning.

## Authors

* **Sebastien Colladon** - *Initial work* - [scolladon](https://github.com/scolladon)
* **Kevin Gossent** - *Initial work* - [YohAnim](https://github.com/yohanim)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
