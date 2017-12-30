## Sugar for CNodejs.org

Material UI version of cnodejs.org. Demo:[ http://cnodejs.sugarac.com](http://cnodejs.sugarac.com)

### Tech Stack

Front-end: React 16 + React Router + Mobx + Webpack + Express.js +  Nginx

### Run at Localhost

```
git clone https://github.com/sugarac/react-cnodejs.org
cd react-cnodejs.org
npm i
npm run build
visit localhost:3333 at your browser
```

### Run at Cloud Server \(Linux\)

```
sudo su
cd ~
mkdir projects
git clone https://github.com/sugarac/react-cnodejs.org
cd react-cnodejs.org
npm i
pm2 start process.yml
visit your server's public IP or bound domain at your browser
```



