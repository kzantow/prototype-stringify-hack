In order to use JSON.stringify effectively when prototype (at least the Jenkins variant) is present, you need this.

Like:

    var stringify = require('prototype-stringify-hack');
    
    stringify(someJsonObject);
