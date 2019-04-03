# learn-sails

a [Sails v1](https://sailsjs.com) application

# Step By Step

1. Install sails js globally using npm

   npm install sails -g

2. Create project

   sails new project-name & go to project-name directory

3. Install depedency for db connection (https://sailsjs.com/plugins/databases)

   npm install sails-mongo -> For MongoDB

4. Config db connecttion in config/datastores.js & config/env/production.js (https://sailsjs.com/documentation/reference/configuration/sails-config-datastores)

   default: {
   adapter: 'sails-mongo(driver_name)',
   url: 'mongodb(protoocol_name)://(username):(password)@localhost(host):27017(port)/blog(db_name)'
   }

5. Generate API

   sails generate api artikel(API name)

### Links

- [Sails framework documentation](https://sailsjs.com/get-started)
- [Version notes / upgrading](https://sailsjs.com/documentation/upgrading)
- [Deployment tips](https://sailsjs.com/documentation/concepts/deployment)
- [Community support options](https://sailsjs.com/support)
- [Professional / enterprise options](https://sailsjs.com/enterprise)

### Version info

This app was originally generated on Wed Apr 03 2019 21:03:50 GMT+0700 (Western Indonesia Time) using Sails v1.1.0.

<!-- Internally, Sails used [`sails-generate@1.16.6`](https://github.com/balderdashy/sails-generate/tree/v1.16.6/lib/core-generators/new). -->

<!--
Note:  Generators are usually run using the globally-installed `sails` CLI (command-line interface).  This CLI version is _environment-specific_ rather than app-specific, thus over time, as a project's dependencies are upgraded or the project is worked on by different developers on different computers using different versions of Node.js, the Sails dependency in its package.json file may differ from the globally-installed Sails CLI release it was originally generated with.  (Be sure to always check out the relevant [upgrading guides](https://sailsjs.com/upgrading) before upgrading the version of Sails used by your app.  If you're stuck, [get help here](https://sailsjs.com/support).)
-->
