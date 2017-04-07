# api documentation for  [mean-cli (v0.12.15)](https://github.com/linnovate/mean-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-mean-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mean-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mean-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mean-cli)
#### Simple command line interface for installing and managing MEAN apps

[![NPM](https://nodei.co/npm/mean-cli.png?downloads=true)](https://www.npmjs.com/package/mean-cli)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mean-cli/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-mean-cli_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mean-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mean-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mean-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "https://github.com/linnovate/mean-cli/graphs/contributors"
    },
    "bin": {
        "mean": "./bin/mean",
        "mean-init": "./bin/mean-init",
        "mean-authorize": "./bin/mean-authorize",
        "mean-whoami": "./bin/mean-whoami",
        "mean-login": "./bin/mean-login",
        "mean-addKey": "./bin/mean-addKey",
        "mean-publish": "./bin/mean-publish",
        "mean-search": "./bin/mean-search",
        "mean-register": "./bin/mean-register",
        "mean-postinstall": "./bin/mean-postinstall",
        "mean-preinstall": "./bin/mean-preinstall",
        "mean-install": "./bin/mean-install",
        "mean-uninstall": "./bin/mean-uninstall",
        "mean-docs": "./bin/mean-docs",
        "mean-package": "./bin/mean-package",
        "mean-list": "./bin/mean-list",
        "mean-status": "./bin/mean-status",
        "mean-user": "./bin/mean-user",
        "mean-logout": "./bin/mean-logout",
        "mean-disable": "./bin/mean-disable",
        "mean-enable": "./bin/mean-enable"
    },
    "bugs": {
        "url": "https://github.com/linnovate/mean-cli/issues"
    },
    "contributors": "https://github.com/linnovate/mean-cli/graphs/contributors",
    "dependencies": {
        "async-series": "latest",
        "bower": "^1.3.8",
        "chalk": "^1.1.3",
        "commander": "^2.4.0",
        "crypto": "latest",
        "inquirer": "^1.0.2",
        "lodash": "^4.12.0",
        "mongoose": "~4.4.15",
        "opener": "^1.3.0",
        "progress": "^1.1.8",
        "prompt": "^1.0.0",
        "request": "^2.72.0",
        "shelljs": "^0.7.0"
    },
    "description": "Simple command line interface for installing and managing MEAN apps",
    "devDependencies": {
        "jshint": "^2.5.10",
        "mocha": "^2.4.5",
        "precommit-hook": "^3.0.0",
        "should": "^8.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "caa4af76dffa8a65d038c585efd9248c542d72e8",
        "tarball": "https://registry.npmjs.org/mean-cli/-/mean-cli-0.12.15.tgz"
    },
    "gitHead": "480e0228740e85abf466a9d85e691c299dddec44",
    "homepage": "https://github.com/linnovate/mean-cli#readme",
    "keywords": [
        "mean",
        "meanio",
        "mean.io",
        "mean-cli"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "andrija-hers",
            "email": "andrija.hers@gmail.com"
        },
        {
            "name": "ellman",
            "email": "yonatan@nodeside.com"
        },
        {
            "name": "fyockm",
            "email": "fyockm@gmail.com"
        },
        {
            "name": "linnovate",
            "email": "lior@linnovate.net"
        },
        {
            "name": "oritpersik",
            "email": "orit@linnovate.net"
        },
        {
            "name": "rivkah",
            "email": "rivka@linnovate.net"
        },
        {
            "name": "sarar",
            "email": "sarar@linnovate.net"
        },
        {
            "name": "vapes",
            "email": "vapesk@gmail.com"
        }
    ],
    "name": "mean-cli",
    "optionalDependencies": {},
    "pre-commit": [
        "lint",
        "validate",
        "test"
    ],
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/linnovate/mean-cli.git"
    },
    "scripts": {
        "lint": "jshint .",
        "test": "node node_modules/.bin/mocha test/**/*.js -R spec",
        "validate": "npm ls"
    },
    "version": "0.12.15"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module mean-cli](#apidoc.module.mean-cli)
1.  object <span class="apidocSignatureSpan">mean-cli.</span>install
1.  object <span class="apidocSignatureSpan">mean-cli.</span>scaffold
1.  object <span class="apidocSignatureSpan">mean-cli.</span>utils

#### [module mean-cli.install](#apidoc.module.mean-cli.install)
1.  [function <span class="apidocSignatureSpan">mean-cli.install.</span>init (options)](#apidoc.element.mean-cli.install.init)

#### [module mean-cli.scaffold](#apidoc.module.mean-cli.scaffold)
1.  [function <span class="apidocSignatureSpan">mean-cli.scaffold.</span>packages (name, options)](#apidoc.element.mean-cli.scaffold.packages)

#### [module mean-cli.utils](#apidoc.module.mean-cli.utils)
1.  boolean <span class="apidocSignatureSpan">mean-cli.utils.</span>isWin
1.  [function <span class="apidocSignatureSpan">mean-cli.utils.</span>Progress ()](#apidoc.element.mean-cli.utils.Progress)
1.  [function <span class="apidocSignatureSpan">mean-cli.utils.</span>checkNpmPermission (callback)](#apidoc.element.mean-cli.utils.checkNpmPermission)
1.  [function <span class="apidocSignatureSpan">mean-cli.utils.</span>loadPackageJson (path, callback)](#apidoc.element.mean-cli.utils.loadPackageJson)
1.  [function <span class="apidocSignatureSpan">mean-cli.utils.</span>meanJsonPath ()](#apidoc.element.mean-cli.utils.meanJsonPath)
1.  [function <span class="apidocSignatureSpan">mean-cli.utils.</span>readMeanSync (param)](#apidoc.element.mean-cli.utils.readMeanSync)
1.  [function <span class="apidocSignatureSpan">mean-cli.utils.</span>readToken ()](#apidoc.element.mean-cli.utils.readToken)
1.  [function <span class="apidocSignatureSpan">mean-cli.utils.</span>updateGlobalMeanJson (values, callback)](#apidoc.element.mean-cli.utils.updateGlobalMeanJson)
1.  [function <span class="apidocSignatureSpan">mean-cli.utils.</span>updateMeanJson (path , values, callback)](#apidoc.element.mean-cli.utils.updateMeanJson)



# <a name="apidoc.module.mean-cli"></a>[module mean-cli](#apidoc.module.mean-cli)



# <a name="apidoc.module.mean-cli.install"></a>[module mean-cli.install](#apidoc.module.mean-cli.install)

#### <a name="apidoc.element.mean-cli.install.init"></a>[function <span class="apidocSignatureSpan">mean-cli.install.</span>init (options)](#apidoc.element.mean-cli.install.init)
- description and source-code
```javascript
init = function (options) {
  progress.start();

	options.anonymizedData = (options.privacy === 'Y' ||options.privacy === 'y' );

	series([
      checkPermissions,
      function(done) {
		  cloneMean(options, done);
      },
	  function(done) {
		  updateSettings(options, done);
	  },
	  function(done) {
		  createMeanJson(options, done);
	  },
	  //printMeanIntro,
      function(done) {
        addGitRemote(options.name, done);
      },
	  function(done) {
        renameMeanStarter(options.name, done);
      },
	  function(done) {
	    createLocalUser(options, function(err, user) {
		    console.log();
		    if (user) options.email = user.email;
		    if (err) return done(err);
		    done();
	    });
	  },
    ],function(err) {
      if (err) throw err;
      nextSteps(options.name);
    });

    progress.stop();

}
```
- example usage
```shell
...
    message: 'What would you name your mean app?',
    default: options.name,
    validate: required
  }];

  inquirer.prompt(questions).then(function(results) {
    _.assign(options, results);
    install.init(options, indexCb);
  });
};
...
```



# <a name="apidoc.module.mean-cli.scaffold"></a>[module mean-cli.scaffold](#apidoc.module.mean-cli.scaffold)

#### <a name="apidoc.element.mean-cli.scaffold.packages"></a>[function <span class="apidocSignatureSpan">mean-cli.scaffold.</span>packages (name, options)](#apidoc.element.mean-cli.scaffold.packages)
- description and source-code
```javascript
packages = function (name, options) {

  var pkg = require(process.cwd() + '/package.json');
  var camelName = camelCase(name);

  data = {
    pkgName: name,
    name: camelName,
    class: capitaliseFirstLetter(camelName),
    author: (typeof options.author === 'string' ? options.author : 'mean scaffold'),
    version: pkg.mean || pkg.version
  };

  console.log('Go to #!/' + data.name + '/example to see your default page');

  buildDirectoryStructure();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mean-cli.utils"></a>[module mean-cli.utils](#apidoc.module.mean-cli.utils)

#### <a name="apidoc.element.mean-cli.utils.Progress"></a>[function <span class="apidocSignatureSpan">mean-cli.utils.</span>Progress ()](#apidoc.element.mean-cli.utils.Progress)
- description and source-code
```javascript
Progress = function (){
  var interval, counter;

  function printMsg() {
    switch (counter) {
      case 0:
        console.log('Use 'mean --help' from command line for all CLI options');
        break;
      case 1:
        console.log('Be sure to checkout all the docs on http://mean.io');
        break;
      case 2:
        console.log('This may take a little while depending on your connection speed');
        break;
      case 15:
        console.log('Seems a bit slow. Check your internet connection...');
        break;
      default:
        console.log('Still cloning...');
        break;
    }
    counter++;
  }

  return {
    start: function() {
      counter = 0;
      interval = setInterval(printMsg, 3000);
    },
    stop: function() {
      clearInterval(interval);
    }
  };
}
```
- example usage
```shell
...
var chalk = require('chalk');
var utils = require('./utils');
var mongoCtrl = require('./controllers/mongo');
var series = require('async-series');
var inquirer = require('inquirer');
var prompt = require('prompt');

var progress = new utils.Progress();

exports.init = function(options) {
  progress.start();

	options.anonymizedData = (options.privacy === 'Y' ||options.privacy === 'y' );

	series([
...
```

#### <a name="apidoc.element.mean-cli.utils.checkNpmPermission"></a>[function <span class="apidocSignatureSpan">mean-cli.utils.</span>checkNpmPermission (callback)](#apidoc.element.mean-cli.utils.checkNpmPermission)
- description and source-code
```javascript
checkNpmPermission = function (callback){
  var homeDir = process.env[isWin ? 'USERPROFILE' : 'HOME'];
  var findCmd = 'find ' + homeDir +'/.npm ' + '-user root';
  shell.exec(findCmd, function( status, output){
    var hasRootFiles = output.split(/\r\n|\r|\n/).length;
    if (hasRootFiles > 1){
      console.log (chalk.red('There are ' + hasRootFiles + ' files in your ~/.npm owned by root'));
      console.log(chalk.green('Please change the permissions by running -'), 'chown -R 'whoami' ~/.npm ');
	    return callback('ROOT PERMISSIONS IN NPM');
    }
  });
  callback();
}
```
- example usage
```shell
...
		if (process.getuid) {
			var uid = process.getuid();
			if (  uid === 0) {
				console.log(chalk.red('Installation of mean should not be done as root! bailing out'));
				throw('RUNNING AS ROOT');
			}
		}
		utils.checkNpmPermission(done);
	}
}

/*
function printMeanIntro(done) {
var logo = fs.readFileSync(__dirname + '/../img/logo.txt');
console.log(logo.toString());
...
```

#### <a name="apidoc.element.mean-cli.utils.loadPackageJson"></a>[function <span class="apidocSignatureSpan">mean-cli.utils.</span>loadPackageJson (path, callback)](#apidoc.element.mean-cli.utils.loadPackageJson)
- description and source-code
```javascript
loadPackageJson = function (path, callback) {
  fs.readFile(path, function(err, data) {
    if (err) return callback(err);

    try {
      var pkg = JSON.parse(data.toString());
      pkg.meanVersion = pkg.mean || pkg.version;
      callback(null, pkg);
    } catch (err) {
      return callback(err);
    }
  });
}
```
- example usage
```shell
...
}




/*
function checkoutStableTag(name){
utils.loadPackageJson('./' + name + '/package.json', function (err, data) {
  var stableTag = 'v'+ data.mean;
  console.log('xxx' ,data.mean);
  var tagCmd = 'cd ' + name + '&& git checkout  ' + stableTag;
  shell.exec(tagCmd);
  console.log(chalk.green('Checked out to stable Tag - '), stableTag);
});
...
```

#### <a name="apidoc.element.mean-cli.utils.meanJsonPath"></a>[function <span class="apidocSignatureSpan">mean-cli.utils.</span>meanJsonPath ()](#apidoc.element.mean-cli.utils.meanJsonPath)
- description and source-code
```javascript
meanJsonPath = function () {
	var file = (process.platform === 'win32') ? '_mean' : '.mean';
	var path = getUserHome() + '/' + file;
	return path;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mean-cli.utils.readMeanSync"></a>[function <span class="apidocSignatureSpan">mean-cli.utils.</span>readMeanSync (param)](#apidoc.element.mean-cli.utils.readMeanSync)
- description and source-code
```javascript
readMeanSync = function (param) {
	var value;

	var path = meanJsonPath();

	if (!shell.test('-e', path)) return null;

	var data = fs.readFileSync(path);
	try {
		var json = JSON.parse(data.toString());
		value = json[param];
	} catch (err) {
		value = null;
	}

	return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mean-cli.utils.readToken"></a>[function <span class="apidocSignatureSpan">mean-cli.utils.</span>readToken ()](#apidoc.element.mean-cli.utils.readToken)
- description and source-code
```javascript
readToken = function () {
	var token;

	var path = meanJsonPath();

	if (!shell.test('-e', path)) return null;

	var data = fs.readFileSync(path);
	try {
		var json = JSON.parse(data.toString());
		token = json.token;
	} catch (err) {
		token = shell.cat(path);
		token = token.replace(/(\r\n|\n|\r)/gm,'');
	}

	return token;
}
```
- example usage
```shell
...
}
*/

/*
function createNetworkUser(options, done) {

	if (options.anonymizedData) {
		var token = utils.readToken();
		if (!token)
			registerOrLogin(options, done, function(token) {
				initApp(options.name, token,  done);
			});
		else {
			initApp(options.name, token, done);
		}
...
```

#### <a name="apidoc.element.mean-cli.utils.updateGlobalMeanJson"></a>[function <span class="apidocSignatureSpan">mean-cli.utils.</span>updateGlobalMeanJson (values, callback)](#apidoc.element.mean-cli.utils.updateGlobalMeanJson)
- description and source-code
```javascript
updateGlobalMeanJson = function (values, callback) {

	var path = meanJsonPath();

	fs.lstat(path, function(err, stat) {
		if (err || !stat) {
			writeMeanJson(path, values, function() {
				callback();
			});
		} else {
			fs.readFile(path, function(err, file) {
				if (err) return callback(err);

				try {
					var json = JSON.parse(file.toString());

					for (var index in values)
						json[index] = values[index];

				writeMeanJson(path, json, function(err) {
					callback(err);
				});

				} catch (err) { // old mean-cli
					var data = {};
					data = values;
					data.token = readToken();
					writeMeanJson(path, data, function(err) {
						callback(err);
					});
				}
			});
		}
	});
}
```
- example usage
```shell
...
    utils.updateMeanJson(path, data, function() {
        done();
    });
}

function createMeanJson(options, done) {

	utils.updateGlobalMeanJson({anonymizedData:  options.privacy === 'Y'}, function() {
		done();
	});
}


function checkPermissions(done) {
	if (utils.isWin) {
...
```

#### <a name="apidoc.element.mean-cli.utils.updateMeanJson"></a>[function <span class="apidocSignatureSpan">mean-cli.utils.</span>updateMeanJson (path , values, callback)](#apidoc.element.mean-cli.utils.updateMeanJson)
- description and source-code
```javascript
updateMeanJson = function (path , values, callback) {

    fs.readFile(path, function(err, file) {
        if (err) return callback(err);

        var json = JSON.parse(file.toString());

        for (var index in values)
            json[index] = values[index];

        writeMeanJson(path, json, function(err) {
            callback(err);
        });
    });
}
```
- example usage
```shell
...
    var data = {
        anonymizedData: options.anonymizedData,
        name: options.name
    };

    var path = process.cwd() + '/' + options.name + '/mean.json';

    utils.updateMeanJson(path, data, function() {
        done();
    });
}

function createMeanJson(options, done) {

	utils.updateGlobalMeanJson({anonymizedData:  options.privacy === 'Y'}, function() {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
