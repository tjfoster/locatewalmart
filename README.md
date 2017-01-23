Completion of tutorial found at https://strongloop.com/strongblog/node-js-php-get-started/.

The public folder was not being served as stated in the tutorial.  Found a key to the solution here: https://knowledge.fastsimple.com/wordpress/webdesktop/node-js-mongobd/ (search locatewalmart).  Updated middleware.json files declaration to:

~~~~
  "files": {
      "loopback#static": {
      "params": "$!../public" 
    }
  },
~~~~
Node, MongoDB, Loopback
