# BBEdit AQL Language support

This adds support for syntax highlighting for the ArangoDB Query Language
([AQL](https://www.arangodb.com/docs/stable/aql/)) to BBEdit.


## Installation

In BBEdit navigate to Preferences > Languages > click on the Language Modules link.
Then put the AQL.plist file in the opened directory and restart BBEdit.

Usually this path is: `~/Library/Application\ Support/BBEdit/Language\ Modules/`.


## Source

Keyword and function names have been taken from
[ArangoDB](https://github.com/arangodb/arangodb/blob/37d99de/js/apps/system/_admin/aardvark/APP/react/public/assets/src/mode-aql.js).
