# mynodepackage
It check if the object is empty or not
## Usage
Install the package using npm :
 npm install mynodepackage --save
Then, require the package and use it:
 [Comment: To check if this usage is proper]
 var isNullOrEmpty = require('is-null-or-empty');
 console.log(isNullOrEmpty("")); // true
 console.log(isNullOrEmpty("Hello World")); // false