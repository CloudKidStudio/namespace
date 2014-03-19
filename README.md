namespace
=========

A simple JavaScript utility for creating namespaces and organizing JavaScript classes into different packages (e.g. Java or ActionScript3).

##Usage##

```js
(function(){
	
	// Create a javascript class definition
	var MyUtils = function(){};

	// Assign to a global namespace
	namespace('com.cloudkid.utils').MyUtils = MyUtils;

}());
```

##Installation##

namespace can be install using Bower.

```bash
bower install cloudkid-namespace
```

##License##

Copyright (c) 2014 [CloudKid](http://github.com/cloudkidstudio)

Released under the MIT License.
