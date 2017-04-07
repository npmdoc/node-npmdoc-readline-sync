# api documentation for  [readline-sync (v1.4.7)](https://github.com/anseki/readline-sync)  [![npm package](https://img.shields.io/npm/v/npmdoc-readline-sync.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-readline-sync) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-readline-sync.svg)](https://travis-ci.org/npmdoc/node-npmdoc-readline-sync)
#### Synchronous Readline for interactively running to have a conversation with the user via a console(TTY).

[![NPM](https://nodei.co/npm/readline-sync.png?downloads=true)](https://www.npmjs.com/package/readline-sync)

[![apidoc](https://npmdoc.github.io/node-npmdoc-readline-sync/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-readline-sync%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-readline-sync/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-readline-sync/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-readline-sync/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "anseki",
        "url": "https://github.com/anseki"
    },
    "bugs": {
        "url": "https://github.com/anseki/readline-sync/issues"
    },
    "dependencies": {},
    "description": "Synchronous Readline for interactively running to have a conversation with the user via a console(TTY).",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "001bfdd4c06110c3c084c63bf7c6a56022213f30",
        "tarball": "https://registry.npmjs.org/readline-sync/-/readline-sync-1.4.7.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "40211f1987db7b994d2d0a348f6dac362c6af3af",
    "homepage": "https://github.com/anseki/readline-sync",
    "keywords": [
        "readline",
        "synchronous",
        "interactive",
        "prompt",
        "question",
        "password",
        "cli",
        "tty",
        "command",
        "repl",
        "keyboard",
        "wait",
        "block"
    ],
    "license": "MIT",
    "main": "./lib/readline-sync.js",
    "maintainers": [
        {
            "name": "anseki",
            "email": "AnSeki.aff@gmail.com"
        }
    ],
    "name": "readline-sync",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/anseki/readline-sync.git"
    },
    "scripts": {},
    "title": "readlineSync",
    "version": "1.4.7"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module readline-sync](#apidoc.module.readline-sync)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>_DBG_clearHistory ()](#apidoc.element.readline-sync._DBG_clearHistory)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>_DBG_set_checkMethod (val)](#apidoc.element.readline-sync._DBG_set_checkMethod)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>_DBG_set_checkOptions (val)](#apidoc.element.readline-sync._DBG_set_checkOptions)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>_DBG_set_useExt (val)](#apidoc.element.readline-sync._DBG_set_useExt)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>getRawInput ()](#apidoc.element.readline-sync.getRawInput)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>keyIn (query, options)](#apidoc.element.readline-sync.keyIn)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>keyInPause (query, options)](#apidoc.element.readline-sync.keyInPause)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>keyInSelect (items, query, options)](#apidoc.element.readline-sync.keyInSelect)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>keyInYN (query, options)](#apidoc.element.readline-sync.keyInYN)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>keyInYNStrict (query, options)](#apidoc.element.readline-sync.keyInYNStrict)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>prompt (options)](#apidoc.element.readline-sync.prompt)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>promptCL (commandHandler, options)](#apidoc.element.readline-sync.promptCL)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>promptCLLoop (commandHandler, options)](#apidoc.element.readline-sync.promptCLLoop)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>promptLoop (inputHandler, options)](#apidoc.element.readline-sync.promptLoop)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>promptSimShell (options)](#apidoc.element.readline-sync.promptSimShell)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>question (query, options)](#apidoc.element.readline-sync.question)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>questionEMail (query, options)](#apidoc.element.readline-sync.questionEMail)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>questionFloat (query, options)](#apidoc.element.readline-sync.questionFloat)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>questionInt (query, options)](#apidoc.element.readline-sync.questionInt)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>questionNewPassword (query, options)](#apidoc.element.readline-sync.questionNewPassword)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>questionPath (query, options)](#apidoc.element.readline-sync.questionPath)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>setBufferSize ()](#apidoc.element.readline-sync.setBufferSize)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>setDefaultOptions (options)](#apidoc.element.readline-sync.setDefaultOptions)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>setEncoding ()](#apidoc.element.readline-sync.setEncoding)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>setMask ()](#apidoc.element.readline-sync.setMask)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>setPrint ()](#apidoc.element.readline-sync.setPrint)
1.  [function <span class="apidocSignatureSpan">readline-sync.</span>setPrompt ()](#apidoc.element.readline-sync.setPrompt)



# <a name="apidoc.module.readline-sync"></a>[module readline-sync](#apidoc.module.readline-sync)

#### <a name="apidoc.element.readline-sync._DBG_clearHistory"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>_DBG_clearHistory ()](#apidoc.element.readline-sync._DBG_clearHistory)
- description and source-code
```javascript
_DBG_clearHistory = function () { lastInput = ''; inputHistory = []; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.readline-sync._DBG_set_checkMethod"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>_DBG_set_checkMethod (val)](#apidoc.element.readline-sync._DBG_set_checkMethod)
- description and source-code
```javascript
_DBG_set_checkMethod = function (val) { _DBG_checkMethod = val; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.readline-sync._DBG_set_checkOptions"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>_DBG_set_checkOptions (val)](#apidoc.element.readline-sync._DBG_set_checkOptions)
- description and source-code
```javascript
_DBG_set_checkOptions = function (val) { _DBG_checkOptions = val; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.readline-sync._DBG_set_useExt"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>_DBG_set_useExt (val)](#apidoc.element.readline-sync._DBG_set_useExt)
- description and source-code
```javascript
_DBG_set_useExt = function (val) { _DBG_useExt = val; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.readline-sync.getRawInput"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>getRawInput ()](#apidoc.element.readline-sync.getRawInput)
- description and source-code
```javascript
getRawInput = function () { return rawInput; }
```
- example usage
```shell
...
'''

See also ['limit' option for 'keyIn*' method](#basic_options-limit-for_keyin_method).

## Special method 'getRawInput'

'''js
rawInput = readlineSync.getRawInput()
'''

Return a raw input data of last method.
When the input was terminated with no data, a 'NULL' is inserted to the data.

This might contain control-codes (e.g. 'LF', 'CR', 'EOF', etc.), therefore, it might be used to get '^D' that was input. But you
 should understand each environments for that. Or, **you should not use this** if your script is used in multiple environments.
For example, when the user input 'EOF' ('^D' in Unix like system, '^Z' in Windows), 'x1A' ('EOF') is returned in Windows, and 'x00
' ('NULL') is returned in Unix like system. And 'x04' ('EOT') is returned in Unix like system with raw-mode. And also, when [external
 program](#note-reading_by_external_program) is used, nothing is returned. See also [Control characters](#note-control_characters
).
...
```

#### <a name="apidoc.element.readline-sync.keyIn"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>keyIn (query, options)](#apidoc.element.readline-sync.keyIn)
- description and source-code
```javascript
keyIn = function (query, options) {
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  var readOptions = margeOptions(margeOptions(true, options), {
    display:            query,
    keyIn:              true,
    keepWhitespace:     true
  });
  /* eslint-enable key-spacing */

  // char list
  readOptions.limitSrc = readOptions.limit.filter(function(value) {
    var type = typeof value;
    return type === 'string' || type === 'number';
  })
  .map(function(text) { return replacePlaceholder(text + '', getPhCharlist); });
  // pattern
  readOptions.limit = escapePattern(readOptions.limitSrc.join(''));

  ['trueValue', 'falseValue'].forEach(function(optionName) {
    readOptions[optionName] = readOptions[optionName].reduce(function(comps, comp) {
      var type = typeof comp;
      if (type === 'string' || type === 'number') {
        comps = comps.concat((comp + '').split(''));
      } else { comps.push(comp); }
      return comps;
    }, []);
  });

  readOptions.display = replacePlaceholder(readOptions.display + '',
    function(param) { return getPhContent(param, readOptions); });

  return toBool(_readlineSync(readOptions), readOptions);
}
```
- example usage
```shell
...
  MAX = 60, MIN = 0, value = 30, key;
console.log('\n\n' + (new Array(20)).join(' ') +
  '[Z] <- -> [X]  FIX: [SPACE]\n');
while (true) {
  console.log('\x1B[1A\x1B[K|' +
    (new Array(value + 1)).join('-') + 'O' +
    (new Array(MAX - value + 1)).join('-') + '| ' + value);
  key = readlineSync.keyIn('',
    {hideEchoBack: true, mask: '', limit: 'zx '});
  if (key === 'z') { if (value > MIN) { value--; } }
  else if (key === 'x') { if (value < MAX) { value++; } }
  else { break; }
}
console.log('\nA value the user requested: ' + value);
'''
...
```

#### <a name="apidoc.element.readline-sync.keyInPause"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>keyInPause (query, options)](#apidoc.element.readline-sync.keyInPause)
- description and source-code
```javascript
keyInPause = function (query, options) {
  if (query == null) { query = 'Continue...'; }
  if ((!options || options.guide !== false) && (query += '')) {
    query = query.replace(/\s+$/, '') + ' (Hit any key)';
  }
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  exports.keyIn(query, margeOptions({
    // -------- default
    limit:              null
  }, options, {
    // -------- forced
    hideEchoBack:       true,
    mask:               ''
  }));
  // added:     guide
  /* eslint-enable key-spacing */
  return;
}
```
- example usage
```shell
...
A key other than 'Y' and 'N' is not accepted. That is, a return value has no default. Therefore, the user has to tell an own wish
 explicitly. If you want to know a user's wish easily, use ['keyInYN'](#utility_methods-keyinyn) method.

This method works same to ['keyInYN'](#utility_methods-keyinyn) method except that this accept only 'Y' or 'N' key (Therefore, a
 return value is boolean every time). The options also work same to ['keyInYN'](#utility_methods-keyinyn) method.

### <a name="utility_methods-keyinpause"></a>'keyInPause'

'''js
readlineSync.keyInPause([query[, options]])
'''

Display a 'query' to the user if it's specified, and then just wait for a key to be pressed by the user.
This method works like the 'window.alert' method of web browsers. This is used to make the running of script pause and show something
 to the user, or wait for the user to be ready.
By default, any key is accepted. You can change this behavior by specifying ['limit'](#basic_options-limit) option  (e.g. accept
 only a Space Bar).

The 'query' is handled the same as that of the ['question'](#basic_methods-question) method.
...
```

#### <a name="apidoc.element.readline-sync.keyInSelect"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>keyInSelect (items, query, options)](#apidoc.element.readline-sync.keyInSelect)
- description and source-code
```javascript
keyInSelect = function (items, query, options) {
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  var readOptions = margeOptions({
      // -------- default
      hideEchoBack:       false
    }, options, {
      // -------- forced
      trueValue:          null,
      falseValue:         null,
      caseSensitive:      false,
      // limit (by items),
      phContent: function(param) {
        return param === 'itemsCount' ? items.length + '' :
          param === 'firstItem' ? (items[0] + '').trim() :
          param === 'lastItem' ? (items[items.length - 1] + '').trim() : null;
      }
    }),
    // added:     guide, cancel
    keylist = '', key2i = {}, charCode = 49 /* '1' */, display = '\n';
  /* eslint-enable key-spacing */
  if (!Array.isArray(items) || !items.length || items.length > 35) {
    throw ''items' must be Array (max length: 35).';
  }

  items.forEach(function(item, i) {
    var key = String.fromCharCode(charCode);
    keylist += key;
    key2i[key] = i;
    display += '[' + key + '] ' + (item + '').trim() + '\n';
    charCode = charCode === 57 /* '9' */ ? 97 /* 'a' */ : charCode + 1;
  });
  if (!options || options.cancel !== false) {
    keylist += '0';
    key2i['0'] = -1;
    display += '[0] ' +
      (options && options.cancel != null && typeof options.cancel !== 'boolean' ?
        (options.cancel + '').trim() : 'CANCEL') + '\n';
  }
  readOptions.limit = keylist;
  display += '\n';

  if (query == null) { query = 'Choose one from list: '; }
  if ((query += '')) {
    if (!options || options.guide !== false) {
      query = query.replace(/\s*:?\s*$/, '') + ' [$<limit>]: ';
    }
    display += query;
  }

  return key2i[exports.keyIn(display, readOptions).toLowerCase()];
}
```
- example usage
```shell
...
'''

* Let the user choose an item from a list:

'''js
var readlineSync = require('readline-sync'),
  animals = ['Lion', 'Elephant', 'Crocodile', 'Giraffe', 'Hippo'],
  index = readlineSync.keyInSelect(animals, 'Which animal?');
console.log('Ok, ' + animals[index] + ' goes to your room.');
'''

'''console
[1] Lion
[2] Elephant
[3] Crocodile
...
```

#### <a name="apidoc.element.readline-sync.keyInYN"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>keyInYN (query, options)](#apidoc.element.readline-sync.keyInYN)
- description and source-code
```javascript
keyInYN = function (query, options) { return _keyInYN(query, options); }
```
- example usage
```shell
...
Oh, CookieMonster loves tofu!
'''

* Get the user's response by a single key without the Enter key:

'''js
var readlineSync = require('readline-sync');
if (readlineSync.keyInYN('Do you want this module?')) {
// 'Y' key was pressed.
console.log('Installing now...');
// Do something...
} else {
// Another key was pressed.
console.log('Searching another...');
// Do something...
...
```

#### <a name="apidoc.element.readline-sync.keyInYNStrict"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>keyInYNStrict (query, options)](#apidoc.element.readline-sync.keyInYNStrict)
- description and source-code
```javascript
keyInYNStrict = function (query, options) { return _keyInYN(query, options, 'yn'); }
```
- example usage
```shell
...
Do you like me? [y/n]: y
Really? [y/n]: y
'''

### <a name="utility_methods-keyinynstrict"></a>'keyInYNStrict'

'''js
boolYes = readlineSync.keyInYNStrict([query[, options]])
'''

Display a 'query' to the user if it's specified, and then accept only 'Y' or 'N' key, and then return a boolean immediately it was
 pressed by the user, **without pressing the Enter key**. Note that the user has no chance to change the input.
This method works like the 'window.confirm' method of web browsers. A return value means "Yes" or "No" the user said. It differ
depending on the pressed key:

* 'Y': 'true'
* 'N': 'false'
...
```

#### <a name="apidoc.element.readline-sync.prompt"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>prompt (options)](#apidoc.element.readline-sync.prompt)
- description and source-code
```javascript
prompt = function (options) {
  var readOptions = margeOptions(true, options);
  readOptions.display = readOptions.prompt;
  return getValidLine(readOptions);
}
```
- example usage
```shell
...
  defaultInput: 'firefox'
});
'''

### <a name="basic_methods-prompt"></a>'prompt'

'''js
input = readlineSync.prompt([options])
'''

Display a prompt-sign (see ['prompt'](#basic_options-prompt) option) to the user, and then return the input from the user after
it has been typed and the Enter key was pressed.
You can specify an 'options' (see [Basic Options](#basic_options)) to control the behavior (e.g. refusing unexpected input, avoiding
 trimming white spaces, etc.).

For example:
...
```

#### <a name="apidoc.element.readline-sync.promptCL"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>promptCL (commandHandler, options)](#apidoc.element.readline-sync.promptCL)
- description and source-code
```javascript
promptCL = function (commandHandler, options) {
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  var readOptions = margeOptions({
      // -------- default
      hideEchoBack:       false,
      limitMessage:       'Requested command is not available.',
      caseSensitive:      false,
      history:            true
    }, options),
      // -------- forced
      // trueValue, falseValue, keepWhitespace don't work.
      // preCheck, limit (by clHandler)
    clHandler = getClHandler(commandHandler, readOptions);
  /* eslint-enable key-spacing */
  readOptions.limit = clHandler.limit;
  readOptions.preCheck = clHandler.preCheck;
  exports.prompt(readOptions);
  return clHandler.args;
}
```
- example usage
```shell
...
##### <a name="utility_methods-questionpath-additional_placeholders-min_max"></a>'min', 'max'

A current value of ['min' and 'max'](#utility_methods-questionpath-options-min_max) option.

### <a name="utility_methods-promptcl"></a>'promptCL'

'''js
argsArray = readlineSync.promptCL([commandHandler[, options]])
'''

Display a prompt-sign (see ['prompt'](#basic_options-prompt) option) to the user, and then consider the input as a command-line
and parse it, and then return a result after the Enter key was pressed.
A return value is an Array that includes the tokens that were parsed. It parses the input from the user as the command-line, and
 it interprets whitespaces, quotes, etc., and it splits it to tokens properly. Usually, a first element of the Array is command-
name, and remaining elements are arguments.

For example:
...
```

#### <a name="apidoc.element.readline-sync.promptCLLoop"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>promptCLLoop (commandHandler, options)](#apidoc.element.readline-sync.promptCLLoop)
- description and source-code
```javascript
promptCLLoop = function (commandHandler, options) {
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  var readOptions = margeOptions({
      // -------- default
      hideEchoBack:       false,
      limitMessage:       'Requested command is not available.',
      caseSensitive:      false,
      history:            true
    }, options),
      // -------- forced
      // trueValue, falseValue, keepWhitespace don't work.
      // preCheck, limit (by clHandler)
    clHandler = getClHandler(commandHandler, readOptions);
  /* eslint-enable key-spacing */
  readOptions.limit = clHandler.limit;
  readOptions.preCheck = clHandler.preCheck;
  while (true) {
    exports.prompt(readOptions);
    if (clHandler.hRes) { break; }
  }
  return;
}
```
- example usage
```shell
...
'''

![sample](screen_03.gif)

* Handle the commands repeatedly, such as the shell interface:

'''js
readlineSync.promptCLLoop({
add: function(target, into) {
  console.log(target + ' is added into ' + into + '.');
  // Do something...
},
remove: function(target) {
  console.log(target + ' is removed.');
  // Do something...
...
```

#### <a name="apidoc.element.readline-sync.promptLoop"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>promptLoop (inputHandler, options)](#apidoc.element.readline-sync.promptLoop)
- description and source-code
```javascript
promptLoop = function (inputHandler, options) {
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  var readOptions = margeOptions({
    // -------- default
    hideEchoBack:       false,
    trueValue:          null,
    falseValue:         null,
    caseSensitive:      false,
    history:            true
  }, options);
  /* eslint-enable key-spacing */
  while (true) { if (inputHandler(exports.prompt(readOptions))) { break; } }
  return;
}
```
- example usage
```shell
...
<tr><td><a href="#basic_options-prompt"><code>prompt</code></a></td><td><a href="#basic_options-mask"><code>mask</code></a></td><
td><a href="#basic_options-defaultinput"><code>defaultInput</code></a></td><td><a href="#basic_options-encoding"><code>encoding</
code></a></td><td><a href="#basic_options-buffersize"><code>bufferSize</code></a></td></tr>
<tr><td><a href="#basic_options-print"><code>print</code></a></td><td><a href="#basic_options-cd"><code>cd</code></a></td></tr>
</table>

### <a name="utility_methods-promptloop"></a>'promptLoop'

'''js
readlineSync.promptLoop(inputHandler[, options])
'''

Display a prompt-sign (see ['prompt'](#basic_options-prompt) option) to the user, and then call 'inputHandler' function with the
 input from the user after it has been typed and the Enter key was pressed. Do these repeatedly until 'inputHandler' function returns
 'true'.

For example, the following 2 codes work same:

'''js
...
```

#### <a name="apidoc.element.readline-sync.promptSimShell"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>promptSimShell (options)](#apidoc.element.readline-sync.promptSimShell)
- description and source-code
```javascript
promptSimShell = function (options) {
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  return exports.prompt(margeOptions({
    // -------- default
    hideEchoBack:       false,
    history:            true
  }, options, {
    // -------- forced
    prompt:             (function() {
      return IS_WIN ?
        '$<cwd>>' :
        // 'user@host:cwd$ '
        (process.env.USER || '') +
        (process.env.HOSTNAME ?
          '@' + process.env.HOSTNAME.replace(/\..*$/, '') : '') +
        ':$<cwdHome>$ ';
    })()
  }));
  /* eslint-enable key-spacing */
}
```
- example usage
```shell
...
<tr><td><a href="#basic_options-prompt"><code>prompt</code></a></td><td><a href="#basic_options-mask"><code>mask</code></a></td><
td><a href="#basic_options-defaultinput"><code>defaultInput</code></a></td><td><a href="#basic_options-encoding"><code>encoding</
code></a></td><td><a href="#basic_options-buffersize"><code>bufferSize</code></a></td></tr>
<tr><td><a href="#basic_options-print"><code>print</code></a></td><td><a href="#basic_options-cd"><code>cd</code></a></td></tr>
</table>

### <a name="utility_methods-promptsimshell"></a>'promptSimShell'

'''js
input = readlineSync.promptSimShell([options])
'''

Display a prompt-sign that is similar to that of the user's shell to the user, and then return the input from the user after it
has been typed and the Enter key was pressed.
This method displays a prompt-sign like:

On Windows:
...
```

#### <a name="apidoc.element.readline-sync.question"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>question (query, options)](#apidoc.element.readline-sync.question)
- description and source-code
```javascript
question = function (query, options) {
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  return getValidLine(margeOptions(margeOptions(true, options), {
    display:            query
  }));
  /* eslint-enable key-spacing */
}
```
- example usage
```shell
...

* Simple case:

'''js
var readlineSync = require('readline-sync');

// Wait for user's response.
var userName = readlineSync.question('May I have your name? ');
console.log('Hi ' + userName + '!');

// Handle the secret text (e.g. password).
var favFood = readlineSync.question('What is your favorite food? ', {
  hideEchoBack: true // The typed text on screen is hidden by '*' (default).
});
console.log('Oh, ' + userName + ' loves ' + favFood + '!');
...
```

#### <a name="apidoc.element.readline-sync.questionEMail"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>questionEMail (query, options)](#apidoc.element.readline-sync.questionEMail)
- description and source-code
```javascript
questionEMail = function (query, options) {
  if (query == null) { query = 'Input e-mail address: '; }
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  return exports.question(query, margeOptions({
    // -------- default
    hideEchoBack:       false,
    // http://www.w3.org/TR/html5/forms.html#valid-e-mail-address
    limit:              /^[a-zA-Z0-9.!#$%&'*+\/=?^_'{|}~-]+@[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])?(?:\.[a-zA-Z0-9](?:[a-zA
-Z0-9-]{0,61}[a-zA-Z0-9])?)*$/,
    limitMessage:       'Input valid e-mail address, please.',
    trueValue:          null,
    falseValue:         null
  }, options, {
    // -------- forced
    keepWhitespace:     false,
    cd:                 false
  }));
  /* eslint-enable key-spacing */
}
```
- example usage
```shell
...
['questionEMail'](#utility_methods-questionemail), ['questionNewPassword'](#utility_methods-questionnewpassword), ['questionInt'](#
utility_methods-questionint), ['questionFloat'](#utility_methods-questionfloat), ['questionPath'](#utility_methods-questionpath), ['
promptCL'](#utility_methods-promptcl), ['promptLoop'](#utility_methods-promptloop), ['promptCLLoop'](#utility_methods-promptclloop
), ['promptSimShell'](#utility_methods-promptsimshell), ['keyInYN'](#utility_methods-keyinyn), ['keyInYNStrict'](#utility_methods
-keyinynstrict), ['keyInPause'](#utility_methods-keyinpause), ['keyInSelect'](#utility_methods-keyinselect)

These are convenient methods that are extended [Basic Methods](#basic_methods) to be used easily.

### <a name="utility_methods-questionemail"></a>'questionEMail'

'''js
email = readlineSync.questionEMail([query[, options]])
'''

Display a 'query' to the user if it's specified, and then accept only a valid e-mail address, and then return it after the Enter
 key was pressed.

The 'query' is handled the same as that of the ['question'](#basic_methods-question) method.
The default value of 'query' is ''Input e-mail address: ''.
...
```

#### <a name="apidoc.element.readline-sync.questionFloat"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>questionFloat (query, options)](#apidoc.element.readline-sync.questionFloat)
- description and source-code
```javascript
questionFloat = function (query, options) {
  return _questionNum(query, options, parseFloat);
}
```
- example usage
```shell
...
<tr><td><a href="#basic_options-hideechoback"><code>hideEchoBack</code></a></td><td><a href="#basic_options-mask"><code>mask</code
></a></td><td><a href="#basic_options-defaultinput"><code>defaultInput</code></a></td><td><a href="#basic_options-encoding"><code
>encoding</code></a></td><td><a href="#basic_options-buffersize"><code>bufferSize</code></a></td></tr>
<tr><td><a href="#basic_options-print"><code>print</code></a></td><td><a href="#basic_options-history"><code>history</code></a></
td></tr>
</table>

### <a name="utility_methods-questionfloat"></a>'questionFloat'

'''js
numFloat = readlineSync.questionFloat([query[, options]])
'''

Display a 'query' to the user if it's specified, and then accept only an input that can be interpreted as a floating-point number
, and then return the number (not string) after the Enter key was pressed.
This parses the input as much as possible by 'parseFloat()'. For example, it interprets ''   3.14   '', ''003.1400'', ''314e-2''
and ''3.14PI'' as '3.14'.

The 'query' is handled the same as that of the ['question'](#basic_methods-question) method.
...
```

#### <a name="apidoc.element.readline-sync.questionInt"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>questionInt (query, options)](#apidoc.element.readline-sync.questionInt)
- description and source-code
```javascript
questionInt = function (query, options) {
  return _questionNum(query, options, function(value) { return parseInt(value, 10); });
}
```
- example usage
```shell
...
##### <a name="utility_methods-questionnewpassword-additional_placeholders-length"></a>'length'

A current value of ['min' and 'max'](#utility_methods-questionnewpassword-options-min_max) option that is converted to human readable
. (e.g. ''12...24'')

### <a name="utility_methods-questionint"></a>'questionInt'

'''js
numInt = readlineSync.questionInt([query[, options]])
'''

Display a 'query' to the user if it's specified, and then accept only an input that can be interpreted as an integer, and then return
 the number (not string) after the Enter key was pressed.
This parses the input as much as possible by 'parseInt()'. For example, it interprets ''   5   '', ''5.6'', ''005'', ''5files'', ''
5kb'' and ''5px'' as '5'.

The 'query' is handled the same as that of the ['question'](#basic_methods-question) method.
...
```

#### <a name="apidoc.element.readline-sync.questionNewPassword"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>questionNewPassword (query, options)](#apidoc.element.readline-sync.questionNewPassword)
- description and source-code
```javascript
questionNewPassword = function (query, options) {
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  var resCharlist, min, max,
    readOptions = margeOptions({
      // -------- default
      hideEchoBack:       true,
      mask:               '*',
      limitMessage:       'It can include: $<charlist>\n' +
                            'And the length must be: $<length>',
      trueValue:          null,
      falseValue:         null,
      caseSensitive:      true
    }, options, {
      // -------- forced
      history:            false,
      cd:                 false,
      // limit (by charlist etc.),
      phContent: function(param) {
        return param === 'charlist' ? resCharlist.text :
          param === 'length' ? min + '...' + max : null;
      }
    }),
    // added:     charlist, min, max, confirmMessage, unmatchMessage
    charlist, confirmMessage, unmatchMessage,
    limit, limitMessage, res1, res2;
  /* eslint-enable key-spacing */
  options = options || {};

  charlist = replacePlaceholder(
    options.charlist ? options.charlist + '' : '$<!-~>', getPhCharlist);
  if (isNaN(min = parseInt(options.min, 10)) || typeof min !== 'number') { min = 12; }
  if (isNaN(max = parseInt(options.max, 10)) || typeof max !== 'number') { max = 24; }
  limit = new RegExp('^[' + escapePattern(charlist) +
    ']{' + min + ',' + max + '}$');
  resCharlist = array2charlist([charlist], readOptions.caseSensitive, true);
  resCharlist.text = joinChunks(resCharlist.values, resCharlist.suppressed);

  confirmMessage = options.confirmMessage != null ? options.confirmMessage :
    'Reinput a same one to confirm it: ';
  unmatchMessage = options.unmatchMessage != null ? options.unmatchMessage :
    'It differs from first one.' +
      ' Hit only the Enter key if you want to retry from first one.';

  if (query == null) { query = 'Input new password: '; }

  limitMessage = readOptions.limitMessage;
  while (!res2) {
    readOptions.limit = limit;
    readOptions.limitMessage = limitMessage;
    res1 = exports.question(query, readOptions);

    readOptions.limit = [res1, ''];
    readOptions.limitMessage = unmatchMessage;
    res2 = exports.question(confirmMessage, readOptions);
  }

  return res1;
}
```
- example usage
```shell
...
<tr><td><a href="#basic_options-mask"><code>mask</code></a></td><td><a href="#basic_options-defaultinput"><code>defaultInput</code
></a></td><td><a href="#basic_options-casesensitive"><code>caseSensitive</code></a></td><td><a href="#basic_options-encoding"><code
>encoding</code></a></td><td><a href="#basic_options-buffersize"><code>bufferSize</code></a></td></tr>
<tr><td><a href="#basic_options-print"><code>print</code></a></td><td><a href="#basic_options-history"><code>history</code></a></
td></tr>
</table>

### <a name="utility_methods-questionnewpassword"></a>'questionNewPassword'

'''js
password = readlineSync.questionNewPassword([query[, options]])
'''

Display a 'query' to the user if it's specified, and then accept only a valid password, and then request same one again, and then
 return it after the Enter key was pressed.
It's the password, or something that is the secret text like the password.
You can specify the valid password requirement to the options.

The 'query' is handled the same as that of the ['question'](#basic_methods-question) method.
...
```

#### <a name="apidoc.element.readline-sync.questionPath"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>questionPath (query, options)](#apidoc.element.readline-sync.questionPath)
- description and source-code
```javascript
questionPath = function (query, options) {
<span class="apidocCodeCommentSpan">  /* eslint-disable key-spacing */
</span>  var validPath, error = '',
    readOptions = margeOptions({
      // -------- default
      hideEchoBack:       false,
      limitMessage:       '$<error(\n)>Input valid path, please.' +
                            '$<( Min:)min>$<( Max:)max>',
      history:            true,
      cd:                 true
    }, options, {
      // -------- forced
      keepWhitespace:     false,
      limit: function(value) {
        var exists, stat, res;
        value = replaceHomePath(value, true);
        error = ''; // for validate
        // mkdir -p
        function mkdirParents(dirPath) {
          dirPath.split(/\/|\\/).reduce(function(parents, dir) {
            var path = pathUtil.resolve((parents += dir + pathUtil.sep));
            if (!fs.existsSync(path)) {
              fs.mkdirSync(path);
            } else if (!fs.statSync(path).isDirectory()) {
              throw new Error('Non directory already exists: ' + path);
            }
            return parents;
          }, '');
        }

        try {
          exists = fs.existsSync(value);
          validPath = exists ? fs.realpathSync(value) : pathUtil.resolve(value);
          // options.exists default: true, not-bool: no-check
          if (!options.hasOwnProperty('exists') && !exists ||
              typeof options.exists === 'boolean' && options.exists !== exists) {
            error = (exists ? 'Already exists' : 'No such file or directory') +
              ': ' + validPath;
            return false;
          }
          if (!exists && options.create) {
            if (options.isDirectory) {
              mkdirParents(validPath);
            } else {
              mkdirParents(pathUtil.dirname(validPath));
              fs.closeSync(fs.openSync(validPath, 'w')); // touch
            }
            validPath = fs.realpathSync(validPath);
          }
          if (exists && (options.min || options.max ||
              options.isFile || options.isDirectory)) {
            stat = fs.statSync(validPath);
            // type check first (directory has zero size)
            if (options.isFile && !stat.isFile()) {
              error = 'Not file: ' + validPath;
              return false;
            } else if (options.isDirectory && !stat.isDirectory()) {
              error = 'Not directory: ' + validPath;
              return false;
            } else if (options.min && stat.size < +options.min ||
                options.max && stat.size > +options.max) {
              error = 'Size ' + stat.size + ' is out of range: ' + validPath;
              return false;
            }
          }
          if (typeof options.validate === 'function' &&
              (res = options.validate(validPath)) !== true) {
            if (typeof res === 'string') { error = res; }
            return false;
          }
        } catch (e) {
          error = e + '';
          return false;
        }
        return true;
      },
      // trueValue, falseValue, caseSensitive don't work.
      phContent: function(param) {
        return param === 'error' ? error :
          param !== 'min' && param !== 'max' ? null :
          options.hasOwnProperty(param) ? options[param] + '' : '';
      }
    });
    // added:     exists, create, min, max, isFile, isDirectory, validate
  /* eslint-enable key-spacing */
  options = options || {};

  if (query == null) { query = 'Input path (you can "cd" and "pwd"): '; }

  exports.question(query, readOptions);
  return validPath;
}
```
- example usage
```shell
...

When these were input, do not return, and wait for reinput.

For example:

'''js
while (true) {
  file = readlineSync.questionPath('File: ');
  console.log('-- Specified file is ' + file);
}
'''

'''console
File: cd foo-dir/bar-dir
File: pwd
...
```

#### <a name="apidoc.element.readline-sync.setBufferSize"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>setBufferSize ()](#apidoc.element.readline-sync.setBufferSize)
- description and source-code
```javascript
setBufferSize = function () { return _setOption('bufferSize', arguments); }
```
- example usage
```shell
...
'''js
readlineSync.setDefaultOptions({bufferSize: value});
'''

instead of:

'''js
readlineSync.setBufferSize(value);
'''

### <a name="deprecated_methods_and_options-noechoback_option"></a>'noEchoBack' option

Use ['hideEchoBack'](README.md#basic_options-hideechoback) option instead of it.

### <a name="deprecated_methods_and_options-notrim_option"></a>'noTrim' option
...
```

#### <a name="apidoc.element.readline-sync.setDefaultOptions"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>setDefaultOptions (options)](#apidoc.element.readline-sync.setDefaultOptions)
- description and source-code
```javascript
setDefaultOptions = function (options) {
  defaultOptions = margeOptions(true, options);
  return margeOptions(true); // copy
}
```
- example usage
```shell
...

### <a name="deprecated_methods_and_options-setprint_method"></a>'setPrint' method

Use the ['print'](README.md#basic_options-print) option.
For the [Default Options](README.md#basic_options), use:

'''js
readlineSync.setDefaultOptions({print: value});
'''

instead of:

'''js
readlineSync.setPrint(value);
'''
...
```

#### <a name="apidoc.element.readline-sync.setEncoding"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>setEncoding ()](#apidoc.element.readline-sync.setEncoding)
- description and source-code
```javascript
setEncoding = function () { return _setOption('encoding', arguments); }
```
- example usage
```shell
...
'''js
readlineSync.setDefaultOptions({encoding: value});
'''

instead of:

'''js
readlineSync.setEncoding(value);
'''

### <a name="deprecated_methods_and_options-setmask_method"></a>'setMask' method

Use the ['mask'](README.md#basic_options-mask) option.
For the [Default Options](README.md#basic_options), use:
...
```

#### <a name="apidoc.element.readline-sync.setMask"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>setMask ()](#apidoc.element.readline-sync.setMask)
- description and source-code
```javascript
setMask = function () { return _setOption('mask', arguments); }
```
- example usage
```shell
...
'''js
readlineSync.setDefaultOptions({mask: value});
'''

instead of:

'''js
readlineSync.setMask(value);
'''

### <a name="deprecated_methods_and_options-setbuffersize_method"></a>'setBufferSize' method

Use the ['bufferSize'](README.md#basic_options-buffersize) option.
For the [Default Options](README.md#basic_options), use:
...
```

#### <a name="apidoc.element.readline-sync.setPrint"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>setPrint ()](#apidoc.element.readline-sync.setPrint)
- description and source-code
```javascript
setPrint = function () { return _setOption('print', arguments); }
```
- example usage
```shell
...
'''js
readlineSync.setDefaultOptions({print: value});
'''

instead of:

'''js
readlineSync.setPrint(value);
'''

### <a name="deprecated_methods_and_options-setprompt_method"></a>'setPrompt' method

Use the ['prompt'](README.md#basic_options-prompt) option.
For the [Default Options](README.md#basic_options), use:
...
```

#### <a name="apidoc.element.readline-sync.setPrompt"></a>[function <span class="apidocSignatureSpan">readline-sync.</span>setPrompt ()](#apidoc.element.readline-sync.setPrompt)
- description and source-code
```javascript
setPrompt = function () { return _setOption('prompt', arguments); }
```
- example usage
```shell
...
'''js
readlineSync.setDefaultOptions({prompt: value});
'''

instead of:

'''js
readlineSync.setPrompt(value);
'''

### <a name="deprecated_methods_and_options-setencoding_method"></a>'setEncoding' method

Use the ['encoding'](README.md#basic_options-encoding) option.
For the [Default Options](README.md#basic_options), use:
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
