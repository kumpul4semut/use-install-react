# Install React
1.Install node js
```
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
```
2.Install npm
```
sudo npm install npm@latest -g
```
3.Install react
```
npm install -g create-react-app
```
4.Create react
```
create-react-app awesome-project
```

# Deploy React To Github

1.Install dev depenci
```
npm install gh-pages --save-dev
```
2.setting packege.json
```
"homepage": "http://gitname.github.io/react-gh-pages"

"scripts": {
  //...
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```
3.Create Repository on github

4.Init folder react project
```
git init my-project
```
5.deploy
```
npm run deploy
```
# update npm if error
```
sudo npm update -g create-react-app

and after that create your react app

create-react-app <app-name>
```
