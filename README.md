

OzwilloUtil(Ozwillo node client) is a set of tool to use ozwillo.
Today you can find three parts : 
- FakeLogin to get a token with your account.
- Connection : tool for getting a token from a user
- MongoServiceMerge : tool which help to merge data stored in mondodb with the datacore

today all modules are experimental and not well documented.

Sample_token : is a script to have token

`` nodejs Sample_token.js confile.json ``

Require to execute : 
1.- Install nodejs "sudo apt-get install nodejs"
2.- in package repertory add the required modules : "npm install simple-oauth2" (see http://fedojo.com/module-js340-throw-err-error-cannot-find-module-node-js-error/ )

How to execute sample_token:
1.- Configure the config.js as required. if you want to generate a refresh_token add "offline_access" to the scopes.
2.- Execute the script using nodejs : node Sample_token.js ./config.json
3.- This utility will give a list of information depending on the entries (scopes, tokens, clienIds, etc.)
