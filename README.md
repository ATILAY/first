WHAT I HAVE LEARNT



REACT WEBPACK
https://www.youtube.com/results?search_query=react+webpack

WEBPACK PLUGINS RULES
https://webpack.js.org/concepts/#plugins

WEBPACK REDUX REACT BABEL CONFIG
https://medium.com/@danilosilvadev/webpack-react-redux-babel-config-in-10-minutes-4ad8c4abc8b2


css animation
https://www.w3schools.com/cssref/css3_pr_animation-iteration-count.asp

css animation shake
https://stackoverflow.com/questions/36962903/javascript-shake-html-element/36964181
dom js remove class
https://www.w3schools.com/howto/howto_js_remove_class.asp
hide show DOM element
https://www.geeksforgeeks.org/hide-or-show-elements-in-html-using-display-property/

DOM create element appendchild 
https://www.w3schools.com/jsref/met_node_appendchild.asp
DOM several class adding
https://stackoverflow.com/questions/1988514/javascript-css-how-to-add-and-remove-multiple-css-classes-to-an-element/36117848

http-server   need to install  -g   //globally
https://www.npmjs.com/package/http-server

vs code change default terminal
https://stackoverflow.com/questions/44435697/vscode-change-default-terminal

webpack redux react babel config
https://medium.com/@danilosilvadev/webpack-react-redux-babel-config-in-10-minutes-4ad8c4abc8b2
AJAX and APIS on REACT

https://en.reactjs.org/docs/faq-ajax.html

axios request on react 
https://medium.com/@baphemot/how-to-make-ajax-requests-in-react-a6a52bb5a8b1

position css
https://www.w3schools.com/css/css_positioning.asp

redux without react
https://medium.com/@alaadawabah/redux-without-react-be9dbc3d7b2
https://redux.js.org/basics/example/
https://blog.bam.tech/developer-news/4-ways-to-dispatch-actions-with-redux
https://github.com/reduxjs/redux/blob/master/examples/counter/src/index.js

APPLYMIDDLEWARE FOR ASYC AWAIT  DATA
COK ONEMLI!!!!
https://redux.js.org/api/applymiddleware/
https://redux.js.org/api/store/


DOM button disabled
https://www.w3schools.com/jsref/prop_pushbutton_disabled.asp
https://stackoverflow.com/questions/14750078/style-disabled-button-with-css/14750390






LEARN CODE ACADEMY REACT JS ANGULAR
https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw

page reload code https://www.w3schools.com/jsref/met_loc_reload.asp

ANGULAR DOC
https://angular.io/api/core/ViewChild#description


css to sass converter
https://css2sass.herokuapp.com/


https://blog.fullstacktraining.com/resolving-cant-bind-to-ngfor-since-it-isnt-a-known-property-of-element-error-in-angular/


https://www.w3schools.com/nodejs/nodejs_events.asp



https://erdincuzun.com/node-js/3-3-eventemitter-sinifi/


context vs scope  differences
https://www.youtube.com/watch?v=hDT3IbvH-9I

00

react children
https://www.youtube.com/watch?v=Sq0FoUPxj_c


00

The Request interface of the Fetch API represents a resource request.

https://developer.mozilla.org/en-US/docs/Web/API/Request
https://developer.mozilla.org/en-US/docs/Web/API/Body
https://developer.mozilla.org/en-US/docs/Web/API/Body/json
00

Fetch API
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API

00
15 Ways to Search Google 96% of People Don’t Know About
https://www.youtube.com/watch?v=erZ3IyBCXdY



00
Array.isArray( _arrayOrVariable_ )
// return true or false

00
copying obj  //shallow cloning -->  clones only first level
let obj = {a:1 , b:2}
let clone =  Object.assign({} , obj)

let clone2 = { ...obj }   //spread operator //shallow cloning -->  clones only first level

let superClone = JSON.parse( JSON.stringify( obj ) )  //for deep cloning! otherwise second level passed by ref and its dangerous!


00
copying array
let array = [1,2,3]
let clone = [].concat(array)
00
manipulate same arrray
array.push([5,6])

00
JavaScript-Equality-Table/

https://dorey.github.io/JavaScript-Equality-Table/

if (NaN) { /* does not execute */ }

if (undefined) { /* does not execute */ }

if (null) { /* does not execute */ }

if ("") { /* does not execute */ }

if (0) { /* does not execute */ }

if (false) { /* does not execute */ }

OTHERWUSE EXECUTES!!

00

NaN === NaN
//false
NaN == NaN
//false
typeof NaN
//"number"
What's the typeof NaN?
The type of NaN, which stands for Not a Number is, surprisingly, a number. The reason for this is, in computing, NaN is actually technically a numeric data type. 
00

null == null
//true
null === null
//true
typeof null
"object"


00

typeof null // "object"

The null value is technically a primitive, the way "object" or "number" are primitives. This would typically mean that the type of null should also be "null". However, this is not the case because of a peculiarity with the way JavaScript was first defined.

In the first implementation of JavaScript, values were represented in two parts - a type tag and the actual value. There were 5 type tags that could be used, and the tag for referencing an object was 0. The null value, however, was represented as the NULL pointer, which was 0x00 for most platforms. As a result of this similarity, null has the 0 type tag, which corresponds to an object.

000

ARRAYS
https://www.freecodecamp.org/news/the-complete-guide-to-loops-in-javascript-f5e242921d8c/
000
Array.isArray( [1,2,3] ) // true
Array.isArray( { a: 1 } ) // false

The typeof an array is an object. In JavaScript, arrays are technically objects; just with special behaviours and abilities. For example, arrays have a Array.prototype.length property, which will return the number of elements in the array.


00

What's the typeof class Foo {}?

typeof class Foo {} // "function"

Finally, we have Classes. Classes were introduced in ES2015 (ES6) as a better syntax for prototype-based inheritance. Before Classes, to make an inheritable object, we would have to use a function.

function Dog() { }
Dog.prototype.bark = function() {
    alert("woof!");
}

const snoopy = new Dog();
snoopy.bark() // alert("woof!")


//SAME AS 
//With Classes, we can create the same object this way -

class Dog {
    bark() {
        alert("woof!");
    }
}

const snoopy = new Dog();
snoopy.bark() // alert("woof!")

However, Classes have always just been a syntactical wrapper around the function method. The same function is actually being created, but just with the author writing it in a different, cleaner way. This is why the typeof a Class, is still just a Function.

00
https://bitsofco.de/javascript-typeof/

00

(function() {
    'use strict';

    return this;
}).call(null); // null


(function() {
    'use strict';

    return this;
})(); // undefined

The first argument for Function.prototype.call is the context, which defines the this value for the execution context of the invoked function, nothing else.

So basically, you're saying that this is referring to null (at least, in ES5 strict mode), but since you don't access this anyway, it makes no difference.

In non-strict mode, this cannot be null, so it's replaced with the global object instead.

https://stackoverflow.com/questions/11659134/applying-a-function-to-null-in-javascript

00

!!!!!!!!!!ECMA ALL DOCUMENTATION!!!!!!
https://www.ecma-international.org/ecma-262/5.1/

00
The Abstract Equality Comparison Algorithm
https://www.ecma-international.org/ecma-262/5.1/#sec-11.9.3

00

when ==  is the issue  it  gets interesting

https://javascript.info/comparison

00

For a non-strict check ==
There’s a special rule. These two are a “sweet couple”: they equal each other (in the sense of ==), but not any other value.

alert( null == undefined ); // true

00
Strange result: null vs 0
Let’s compare null with a zero:



                               alert( null > 0 );  // (1) false
alert( null == 0 ); // (2) false
alert( null >= 0 ); // (3) true
Mathematically, that’s strange. The last result states that "null is greater than or equal to zero", so in one of the comparisons above it must be true, but they are both false.

The reason is that an equality check == and comparisons > < >= <= work differently. Comparisons convert null to a number, treating it as 0. That’s why (3) null >= 0 is true and (1) null > 0 is false.

On the other hand, the equality check == for undefined and null is defined such that, without any conversions, they equal each other and don’t equal anything else. That’s why (2) null == 0 is false.

00

An incomparable undefined
The value undefined shouldn’t be compared to other values:

alert( undefined > 0 ); // false (1)
alert( undefined < 0 ); // false (2)
alert( undefined == 0 ); // false (3)
Why does it dislike zero so much? Always false!

We get these results because:

Comparisons (1) and (2) return false because undefined gets converted to NaN and NaN is a special numeric value which returns false for all comparisons.
The equality check (3) returns false because undefined only equals null, undefined, and no other value.
Evade 


00

5 > 4 → true
"apple" > "pineapple" → false
"2" > "12" → true
undefined == null → true
undefined === null → false
null == "\n0\n" → false
null === +"\n0\n" → false
Some of the reasons:

Obviously, true.
Dictionary comparison, hence false. "a" is smaller than "p".
Again, dictionary comparison, first char of "2" is greater than the first char of "1".
Values null and undefined equal each other only.
Strict equality is strict. Different types from both sides lead to false.
Similar to (4), null only equals undefined.
Strict equality of different types.

https://javascript.info/comparison

00
Prototype inheritance
lizard.__proto__ = dragon;

for ( let prop in lizard ){ console.log( prop )  }
 
//name
//fight
//fire
//sing
00

hasOwnProperty()

lizard.__proto__ = dragon;

for ( let prop in lizard ){ if( lizard.hasOwnProperty( prop ) ) console.log( prop )  }
//name
//fight  -->> others are inherited by prototypical


00

let human = {
	mortal: true
}
let socrates = Object.create( human )
//created prototypical inheritantly
socrates.age = 45

console.log( human.isPrototypeOf( socrates ) )
//true
console.log( socrates )
//{ age: 45 }
//--> there is not seen 'mortal' because it have been taken inheritantly prototypical!

00
typeof {}
//"object"

typeof Object
//"function"  --> because it has constructor function to create (wrap) an object

00

Object.__proto__ 
//null

00
"string".prototype
//undefined
String.prototype
// yes there is  prototype because String is an constructor func
typeof String
//"function"

00
!!!!!!!!!!!ONLY FUNCTIONS HAVE THE PROTOTYPE PROPERTY!!!!!!!!!!
00

Date.prototype.lastYear = function(){

	console.log( this )
	return  this.getFullYear() - 1; 
	/////!!!!!!!/ -> if I use ()=>{} here  this gonna be crashed because arrow func lexicallay scoped!!


}
new Date('1900-10-10').lastYear()
//'1899'


00









































































https://www.w3schools.com/jsref/jsref_splice.asp





https://www.npmjs.com/package/@angular/cli


https://appdividend.com/2019/06/06/angular-8-httpclient-example-how-to-send-ajax-request-in-angular/



https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c



https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c



https://www.udemy.com/course/bootstrap-4-beta-ultimate-projects-course/



https://www.youtube.com/watch?v=OxIDLw0M-m0&list=PL4cUxeGkcC9ij8CfkAY2RAGb-tmkNwQHG

https://www.udemy.com/course/react-native-the-practical-guide/?couponCode=ACAD_0120














-------------------------------------------------
00 cal backs Promises RXJS observables ASYC await 
https://www.youtube.com/watch?v=jgWnccjXR4I

00
event emitter
https://www.w3schools.com/nodejs/nodejs_events.asp

00
https://blog.fullstacktraining.com/resolving-cant-bind-to-ngfor-since-it-isnt-a-known-property-of-element-error-in-angular/
ngFor cant binding  and @input()   data passing


00
import { FormsModule } from '@angular/forms';
https://stackoverflow.com/questions/38892771/cant-bind-to-ngmodel-since-it-isnt-a-known-property-of-input

00
redux babel    es5 to es6
https://babeljs.io/repl#?browsers=&build=&builtIns=false&spec=false&loose=false&code_lz=FAYw9gdgzgLgBAJwKYBMCuAPOBeOikCOaAlsgBQDky6GFAlKJLHCMgIYxIDKMYyO-GgDpWSDt17JG0eGwAOcgDYBPALLEUKRUgDubfrmqYh8pWo1bd-pHGnMYACzQQA1us3a9B_EVJJKRhgAtI7OLvRCKEgAZmxoijB2shjEYFACyL7kFGwpafTAheAycABiAKIAKgDCABIA-gCqXOUASlz1reUAio3lXJUCFBU1Dc1tHV29_ZUUSWVVdU0t7fVcjdXV_VxDI0vjq-ub23PFzHtjKx2lAIIAkgAyjV27i5cT9bePz-VzwAD0_zYIBgqQgwGizhBYLg0SQMBADkaUCQCCgrUIaCQzDIdDgAG9gHg8MgYGgEBACUTiTSYMo5EgAFwLUbLD5TPoDal4AC-wD5kIg0MgsPhiORqKgXDQIBA2PSZDQKLReMJNNJ5MpappxLpDOZFzZhw2Wy4XAANNydXI2MpFGA2ChmUrJVa-QKoaCRXCEUjlVBSmxiIpyTYyKiEHw6NqSfDNVSdbr6UyWfsrp97k8upbE3gbXaHU64BG-G7-YVCoCjHKEAD_nAyHJkAA3VJKnjiODmuDAr0QOjYAB8hMBeAgug7nDrfLrsHE82IEGIoLYiknNlwMbg9sdi4A5szYooUTniS60cyANoAXVPeBLCGZFDmM6rqBlqPm1dRAjIc84AiLsuxCruu3a9mCA7DlaUA6MuiJkBBkBCHqSDRlaNIgGwKKpu8qxfFm5TMhqFIJrmNJCJR_5IHe5HboW-6HquJ4YbmD7MgABm0rQAPKtIyzIACT4khEBCPmO4oDyHGFORfLkVhOGGgckw9JylTEXGpFbuRlFCNRtHkZJjFwDACBYqxvKWSw2E2Mp6ZHKaXCaWS2nWRRVEwOIhm5sZEAHrCzE0e5Z7-syonibakk-Ym1nycS7p1j6iJwM0rpnPAyV-pKv5QVugIQHwAC2q4qD2wqUqIHB8OkQSDvgrnQOVfZwGAABGABWVqApUtSNAAcgA0nA7iWF4Nh1XATZgK2UTpI4HDNWC6QOGwzY2GwbXBsuyimWADXxqUA3VJUdw8f1XAAISXVaJGUoKFVkHAKDEFANq-nA6HkYCAAiPH9P1gy1DcABq5RwJUPFwAAQuDAAKPxwBQDgwDAchQIygJFagxBoEVIhgEV_wAAIdWw2NQB1MRwggyhoC4_xk822GsMQcgwEEOirRz1hBHIoZBA9fZQEEAAsKDiwArAAzAAnAATBLssgHM33_HcsiKPaOjYqZDg2FAGg2NTSAgnARy1HANw7JN1sAJr9dUVsAOr3IMNxw3ccDVDcDwPFw1mAo4r2wlCPbHvtWGUi9b29g4PaUqJeuLcuFDpCiSCUm1MR8Eg1354H_xcFDy42ZSyBysQ609s9r02iC8fY44YAoFbOw3P1VutAA4o0qjlIDBfWTH70IVlEpohiRDYjAuIMNZuSpFAQh7vClAo2jGOAh1UCQEowJIA4YCKFECAofSxDgFEBNE-eUAFHRxIofrEBPcgUBDjpj9wG-y8oBwbA8BBHqPVEOesNoIAQLaVq0Q4B3xComDKcD_Q3C1v_LyGRsSRAAbJb-mEmDwDvncVuuA76oJPgAoQJU5BPXPDgeq54hAaHnggnUI8OBjzFNlNE0pZTykVP6YhdB554J5AwPBIgOEOCehGT-rCaSAgjFQ-UbBV5wBDo4Y2kC-B4DmqzdmYJ5HEnYb6J649_SBmDKGcMkDlFQCgKotC4jv5iNwVZV8_wqoAVgLneYPjvBeIkLnN-74azgQUCoUanhrBkFCK4KJVhkB4gYICKAaA2pQFZtnPacB_FIGAHk_S6TMkIGINnJ6uJP4sCYMfJAQh7R7ieoU1eMB1y4k-nAHkn06wmJSsHdI2FlBCiWiKLxpZCm9OkaKX0E90jzwKi3Gwi4ogYCEDvCsQA&debug=false&forceAllTransforms=false&shippedProposals=false&circleciRepo=&evaluate=false&fileSize=false&timeTravel=false&sourceType=module&lineWrap=true&presets=es2015%2Creact%2Cstage-2&prettier=false&targets=&version=7.8.4&externalPlugins=

00
https://codepen.io/pen/

00
Client on node: Uncaught ReferenceError: require is not defined
https://stackoverflow.com/questions/19059580/client-on-node-uncaught-referenceerror-require-is-not-defined

00
git bash
https://git-scm.com/download/win

00
react native useful tutorial
https://www.udemy.com/course/react-native-the-practical-guide/?couponCode=ACAD_0120

00
HttpClientModule
https://appdividend.com/2019/06/06/angular-8-httpclient-example-how-to-send-ajax-request-in-angular/

00
https://stackoverflow.com/questions/10075990/upgrading-node-js-to-latest-version

00
https://github.com/angular/angular-cli/issues/11650

00
https://stackoverflow.com/questions/46623571/angular-ng-command-not-found/49820551

00
https://stackoverflow.com/questions/37227794/ng-command-not-found-while-creating-new-project-using-angular-cli

00
vscode terminal gitbash ng command not found problem
solution:
alias ng=" ~/AppData/Roaming/npm/node_modules/@angular/cli/bin/ng"

https://www.computerworld.com/article/2598087/how-to-use-aliases-in-linux-shell-commands.html

https://github.com/angular/angular-cli/issues/503

https://stackoverflow.com/questions/46623571/angular-ng-command-not-found/49820551

https://stackoverflow.com/questions/53485885/angular-cli-not-working-in-git-bash-terminal-on-windows

00
https://stackoverflow.com/questions/40820822/location-of-bashrc-for-bash-on-ubuntu-on-windows-in-windows-10

00
https://ovinitech.blogspot.com/2017/08/ng-is-not-recognized-as-internal-or.html

00
https://github.com/angular/angular-cli/issues/5021

00
https://medium.com/@angela.amarapala/ways-to-fix-bash-ng-command-not-found-7f329745795

00
JSONPLACEHOLDER FOR FETCHING USERS 
https://jsonplaceholder.typicode.com/users

00
HttpClientModule
https://appdividend.com/2019/06/06/angular-8-httpclient-example-how-to-send-ajax-request-in-angular/

00
https://www.it-swarm.dev/tr/node.js/npm-err-kod-elifecycle/830100767/

00
https://www.npmjs.com/package/@angular/cli

when ng serve  not found 
npm i @angular/cli

00
https://www.howtogeek.com/196371/master-vlc-with-these-23-keyboard-shortcuts/

00
flex bootstrap
https://getbootstrap.com/docs/4.4/utilities/flex/

00
js splice
Note: This method changes the original array.
adds/removes items to/from an array, and returns the removed item(s).
https://www.w3schools.com/jsref/jsref_splice.asp

00

---
How to Push Project to Github Repository
https://www.youtube.com/watch?v=ibNqauPoicg
----

----------------------------------------------
book ebook pdf torrent websites free bedava  kitap
https://b-ok.cc/
https://b-ok.cc/book
http://gen.lib.rus.ec/book/
https://ekitapcilar.com/tum-zamanlarin-en-kaliteli-e-kitap-arsivi/
https://en.wikibooks.org
https://www.free-ebooks.net/search/john+rich
https://1337x.to/sub/36/0/
https://www.torlock.com
https://www.books-share.com
https://ww1.torrent9.is/torrents_ebook.html
https://www.bookyards.com/en?__cf_chl_jschl_tk__=61a8d6074e9d03c966402b5f1d6498d967c648ef-1582755191-0-AVJatS0VbT66SnP51yuBt_Z3PjLaU4CcfJrRI5qNTTUOlz09F35DMsS1uWRdNCt6eA_KWQQX0mG8EPHGzsPy3FeTuIlodGQRiCmp5NzSQC7HH-9NevHeTAWbi6slMCF0PAtfHdmfc4g4XzDuGZ67nxXfmgPbh4DBtDwE-paU_loHYU0V_BdW5Kyv6uUOQSX8e1sRuQ_DPYcMI4yS4iJ_f_w3CmLT2HfgHa-IW5WXpJEfGNRbD7dNicZEPNDFVcO1-wDLE1J2XV2kM7PDhlkkNRc
https://www.seedpeer.me/home
http://copypasteprogrammers.com/best-torrent-sites-download-e-books-html/

https://opentrackers.org/downloading-ebooks-textbooks/
---------------------------------------------------------


