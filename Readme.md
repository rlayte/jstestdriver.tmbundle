
# JsTestDriver Bundle

A collection of snippets and commands for use with Google's JsTestDriver unit testing framework.

## Snippets

**Tests**

+ test: test &#x21E5;
+ test case: testcase &#x21E5;
+ dom fixture: dom &#x21E5;
+ dom variable: domvar &#x21E5;
+ console.log: log &#x21E5;

**Assertions**

+ assertTrue: at &#x21E5;
+ assertFalse: af &#x21E5;
+ assertEquals: ae &#x21E5;
+ assertNotEquals: ane &#x21E5;
+ assertSame: as &#x21E5;
+ assertNotSame: ans &#x21E5;
+ assertUndefined: au &#x21E5;
+ assertNotUndefined: anu &#x21E5;
+ assertNaN: anan &#x21E5;
+ assertNotNaN: annan &#x21E5;
+ assertException: aex &#x21E5;
+ assertNotException: anex &#x21E5;
+ assertMatch: am &#x21E5;
+ assertNoMatch: anm &#x21E5;
+ assertTypeof: ato &#x21E5;
+ assertInstanceOf: aio &#x21E5;
+ assertArray: aa &#x21E5;
+ assertFunction: af &#x21E5;
+ assertObject: ao &#x21E5;
+ assertNumber: anum &#x21E5;
+ assertString: astr &#x21E5;
+ assertBoolean: ab &#x21E5;
+ assertTagName: atn &#x21E5;
+ assertClassName: acn &#x21E5;
+ assertElementId: aei &#x21E5;

## Starting the server

&#x2318; + k

This will open a new window, which runs the server. To stop the server just close this window.

## Running tests

&#x2318; + j

This will reset the runner, run all tests, and output the results to an html window.

Note: These commands are still at an early stage and are currently pretty crude. The port is hardcoded to 4224, which can be changed by editing the command in the bundle. It also assumes a directory structure, which means you need to run the command from a sub directory of the folder that contains the configuration file. Again this can be changed in the bundle editor. Both of these will be made more easily configurable shortly.

## How To Install

**Using git**

Open Terminal and navigate to the Textmate application support folder, i.e.

`cd ~/Library/Application\ Support/TextMate/Bundles/`

Clone the git repository

`git clone git@github.com:rlayte/jstestdriver.tmbundle.git`

Reload the bundles either from the Textmate menu or

`osascript -e 'tell app "TextMate" to reload bundles'`

**Without git**

+ click on the download soruce link near the top of the page.
+ unzip and rename folder to jstestdriver.tmbundle
+ double click on the bundle

## License 

(The MIT License)

Copyright (c) 2010 Richard Layte

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.