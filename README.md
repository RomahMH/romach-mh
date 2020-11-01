# romach-mh

# How to update a package (Make sure you running with node 10.15.1 or 10.1.0)
1. Add it to the package.json file (Make sure the json file is valid)
2. run `npm install`
3. Copy `romach-icons` folder inside the `node_modules` folder (**after installation**)
4. Add `"romach-icons": "1.0.0"` to `package.json` file (make sure it is valid)
5. **7zip** (not rar) the `node_modules` folder and the `package.json` file
6. Remove the `"romach-icons"` line from `package.json` and commit
7. Push the `package.json` file to this repository
8. White the 7Zip file
