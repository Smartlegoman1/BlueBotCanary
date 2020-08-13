# 2PG - Glitch Demo
This demo was created on `03/08/2020`.

## Update `config.json`
Add your values

## Update Music Servers
```
const nodes = [{
  host: '[yourHerokuAppName].herokuapp.com',
  port: 2333,
  password: 'youshallnotpass',
}];
```
If you do not have a heroku music server -> [Setup Heroku Music Server](https://heroku.com/deploy?template=https://github.com/IamTheRealSami/LavalinkOnHeroku/tree/auto).

## Add Redirect URIs
![Redirects](https://i.ibb.co/9pbfVwL/updated-redirects.png)
at [https://discord.com/developers](https://discord.com/developers)