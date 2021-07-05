<p align="center">
  <a href="https://forwardigital.co.uk/" target="blank"><img src="https://forwardigital.co.uk/logos/logo.svg" width="350" alt="Forward Digital Logo" /></a>
</p>

# npm-package-base
This is a repository template for building npm packages in JavaScript/TypeScript. 

## Prerequisites
You will want to make sure that you are logged in to your NPM account from your CLI. This will ensure that you can successfully
publish your package to your account. You can do this with the following command
```
npm login
```

## Building the package
Once you have written all of your code inside the ``/src`` directory you will need to build your package. 
Building your package will create a ``/lib`` directory. This contains your types and your packages entry points.
Run the following command to build your package:
```
npm run prepare
```

## Publishing the package to npmjs.com
Now you have built your package it is ready to be uploaded to npmjs.com. Once this command is run you will be able to
view your package from the dashboard on npmjs.com. If you make changes to your package then just repeat the build and publish
steps again

```
npm publish
```

NOTE: Make sure you remember to bump the version number and re-run the prepare command before publishing.


## Keywords
Inside the ``package.json`` you can edit the keywords array. These keywords are what appear as tags on npmjs.com.
```json
"keywords": [
    "typescript",
    "npm"
  ]
```
