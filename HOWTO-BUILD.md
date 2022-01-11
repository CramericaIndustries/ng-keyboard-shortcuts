# Development Build with Watch
### switch to the root dir of the project
### build ng-keyboard-shortcuts module/library in watch mode (located in projects/ng-keyboard-shortcuts)
```npm run build:watch```

### build test app in watch mode (in second terminal)
```npm run start```



# Build to export
### build ng-keyboard-shortcuts in porduction mode
```npm run build:prod```
### pack ng-keyboard-shortcuts library
```npm run npm-pack```
### build test app in watch mode
```npm run start```


# Use ng-keyboard-shortcuts in different project from tgz file
```npm run build:prod```
```npm run npm-pack```
### copy the tgz file from
```dist/ng-keyboard-shortcuts/ng-keyboard-shortcuts-13.0.0.tgz```
### to an subfolder of your project. For example:
```external-libs/ng-keyboard-shortcuts/```
### then do
```npm install --save external-libs/ng-keyboard-shortcuts/ng-keyboard-shortcuts-13.0.0.tgz```


## Alternatively install it directly from github
### copy the **ng-keyboard-shortcuts-13.0.0.tgz** file to **bin-releases** folder and commit the file
### to use the lib then do
```npm install --save https://raw.githubusercontent.com/CramericaIndustries/ng-keyboard-shortcuts/master/bin-releases/ng-keyboard-shortcuts-13.0.0.tgz```

