# npm_arguments
 
```
https://stackoverflow.com/questions/11580961/sending-command-line-arguments-to-npm-script

mfadlizein@MacBook-Pro-Zein npm_arguments % npm run argument --foo=tas

https://stackoverflow.com/questions/44947773/download-module-on-npm-start

https://docs.npmjs.com/cli/v8/using-npm/scripts/


//yargs
https://nodejs.org/en/knowledge/command-line/how-to-parse-command-line-arguments/

mfadlizein@MacBook-Pro-Zein npm_arguments % node index-v2.js lyr -y
2022 is NOT a Leap Year
{ _: [ 'lyr' ], y: undefined, year: undefined, '$0': 'index-v2.js' }
mfadlizein@MacBook-Pro-Zein npm_arguments % node index-v2.js -t    
The current time is:  2:19:12 PM
{ _: [], t: true, time: true, '$0': 'index-v2.js' }
mfadlizein@MacBook-Pro-Zein npm_arguments % node index-v2.js -h
index-v2.js [command]

Commands:
  index-v2.js lyr  Tells whether an year is leap year or not

Options:
      --version  Show version number                                   [boolean]
  -t, --time     Tell the present Time                                 [boolean]
  -h, --help     Show help                                             [boolean]
mfadlizein@MacBook-Pro-Zein npm_arguments % 


https://stackoverflow.com/questions/4351521/how-do-i-pass-command-line-arguments-to-a-node-js-program

mfadlizein@MacBook-Pro-Zein npm_arguments % node index-v3.js one two=three four
0: /opt/homebrew/Cellar/node/18.7.0/bin/node
1: /Applications/XAMPP/xamppfiles/htdocs/npm_arguments/index-v3.js
2: one
3: two=three
4: four


mfadlizein@MacBook-Pro-Zein npm_arguments % node index-v4.js one two=three four
[ 'one', 'two=three', 'four' ]
mfadlizein@MacBook-Pro-Zein npm_arguments % node index-v4.js one two=three four
[
  '/opt/homebrew/Cellar/node/18.7.0/bin/node',
  '/Applications/XAMPP/xamppfiles/htdocs/npm_arguments/index-v4.js',
  'one',
  'two=three',
  'four'
]
[ 'one', 'two=three', 'four' ]
```