# readEachLineSync

Read file line by line, synchronously.

# Install

    npm install readEachFileSync

# Example

    var readEachLineSync = require('readEachLineSync')
    
    readEachLineSync('test.txt', 'utf8', function(line) {
      console.log(line)
    })

Encoding can optionally be omitted, in which case it will default to utf-8:

    readEachLineSync('test.txt', function(line) {
      console.log(line)
    })

# Credits

Author: [Geza Kovacs](http://github.com/gkovacs)
Based on [readLineSync](https://gist.github.com/Basemm/9700229)

# License

MIT
