# eslint-config-snownoop
Eslint config npm module

Using for Sublime-Text-3

1. You will need folowing npm packages to be installed
```
npm install -g eslint babel-eslint
```
2. Go to sublime and install following packages:
- SublimeLinter
- SublimeLinter-contrib-eslint

3. Go to project folder and
```
npm link
```

4. Go to project you need eslint inside
5. Create .eslintrc.json
6. Add row
```
"extends": [
    "eslint-config-snownoop"
  ],
```
7. Relaunch Sublime-Text-3

P.S:
> You can create .eslintrc.json on your projects root folder, so all child folders will auto-extend this file, or you can extend it by yourself if it is needed.
