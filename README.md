# eslint-config-snownoop
Eslint config npm module

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
    "eslint-config-snownoop",
    ...
  ],
```
