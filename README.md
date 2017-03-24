**DeriveJS** simply seeks to find different ways of expressing JavaScript, if you have any Ideas, please make PR!

****Goals****
 - Find derivatives for JavaScript types
 - Experiment with the derivation of funky number systems
 - Do something with it - maybe a transpiler or obfuscator
 
 
 

            {
     	"undefined": [
     		"void 0",
     		"[]['']",
     		"0[0]",
     		"0..$",
     		"(function(){})()"
     	],
     	"null": [
     		"\"\".__proto__.__proto__.__proto__",
     		"Object.getPrototypeOf(Object.prototype)",
     		"(new Event(\"\")).target"
     	],
     	"false": [
     		"![]",
     		"!{}",
     		"!!''",
     		"!!\"\"",
     		"!1",
     		"![]",
     		"delete NaN",
     		"0 in []",
     		"0 instanceof Object",
     		"[].some(Object"
    
     	],
     	"true": [
     		"!![]",
     		"!!{}",
     		"!''",
     		"!\"\"",
     		"!0",
     		"!-0",
     		"!NaN",
     		"!\"\"",
     		"delete 0",
     		"0 in [0]",
     		"[] instanceof Object",
     		"isNan()",
     		"[].every(eval)"
     	],
     	"NaN": [
     		"+{}",
     		"0/0",
     		"+undefined",
     		"Math.acos(2)",
     		"Math.log()"
     	],
     	"Infinity": [
     		"1/0",
     		"1e1000",
     		"Math.atanh(1)",
     		"-Math.log(0)"
     	]
     }

****Sources****
 - [https://accents-of-javascript.tumblr.com/post/154385761700/javascript-synonyms](https://accents-of-javascript.tumblr.com/post/154385761700/javascript-synonyms)
 - [http://www.jsfuck.com/](http://www.jsfuck.com/)

Reddit post asking for help 
 - [https://www.reddit.com/r/javascript/comments/5z1f43/input_wanted_building_a_reference_for_neat_ways/](https://www.reddit.com/r/javascript/comments/5z1f43/input_wanted_building_a_reference_for_neat_ways/)
