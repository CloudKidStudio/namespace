namespace
=========

 [![Build Status](https://travis-ci.org/CloudKidStudio/namespace.svg?branch=master)](https://travis-ci.org/CloudKidStudio/namespace) [![Dependency Status](https://david-dm.org/CloudKidStudio/namespace.svg?style=flat)](https://david-dm.org/CloudKidStudio/namespace)

JavaScript utility for creating namespaces and organizing JavaScript classes into different packages.


##Installation

namespace can be install using Bower.

```bash
bower install cloudkid-namespace
```

##Usage

Use `namespace` global function to define your classes within closures. 

```js
(function(){	

	// Create a javascript class definition
	var MyUtils = function(){};

	// Assign to a global namespace
	namespace('com.cloudkid.utils').MyUtils = MyUtils;

}());
```

Use `include` to import a reference to the class. Will throw an error if the class doesn't exist. 

```js
(function(){
	
	// Include the 
	var MyUtils = include('com.cloudkid.utils.MyUtils');

}());
```

##License

Copyright (c) 2015 [CloudKid](http://github.com/cloudkidstudio)

Released under the MIT License.
