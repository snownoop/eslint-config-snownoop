# eslint-config-snownoop
Eslint config npm module

Using for Sublime-Text-3

You will need folowing npm packages to be installed
```
npm install -g eslint babel-eslint
```
Go to sublime and install following packages:
- SublimeLinter
- SublimeLinter-contrib-eslint

Go to project folder and
```
npm link
```
Go to project you need eslint inside

Create .eslintrc.json

Add row
```
"extends": [
    "eslint-config-snownoop"
  ],
```

Relaunch Sublime-Text-3

P.S:
> You can create .eslintrc.json on your projects root folder, so all child folders will auto-extend this file, or you can extend it by yourself if it is needed.
