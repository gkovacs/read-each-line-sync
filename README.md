# read-each-line-sync

Read file line by line, synchronously.

## Install

    npm install read-each-line-sync

## Example

    var readEachLineSync = require('read-each-line-sync')
    
    readEachLineSync('test.txt', 'utf8', function(line) {
      console.log(line)
    })

Encoding can optionally be omitted, in which case it will default to utf8:

    readEachLineSync('test.txt', function(line) {
      console.log(line)
    })

## Credits

Author: [Geza Kovacs](http://github.com/gkovacs)

Based on [readLineSync](https://gist.github.com/Basemm/9700229)

## License

MIT
