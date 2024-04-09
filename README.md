# published to npm

1. `npm init` => to create package.json
2. add npm_name scope to package.json, VD: "name": "@jugen/first-demo-project"
3. `npm login` => OTP code in email
4. `npm publish --access public` (first time)
5. When update project exist => change version and run `npm publish`

# Pull package and update

1. npm pack <package_name>
2. unzip this packe (change name folder, if you want)
3. change version in package.json
4. change code ...
5. Login: `npm login`
6. Publish: `npm publish`
