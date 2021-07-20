# MoonWalker JSON API Documentation
Documentation for [MoonWalker JSON API](https://github.com/MoonWalkerHTTP)

## Prerequisites

- [x] [Node.js](https://nodejs.org)
- [x] [NPM](https://npmjs.org)
- [x] [Git](https://git-scm.com)
- [x] [GitHub CLI (Optional)](https://cli.github.com)

## Introduction 
MoonWalker JSON API is an API creation tool for easier API-building. 

Each Route can be written in JavaScript or JSON. 

Each Route has a folder containing its own files. 

A Route can be linked by updating the `/config/routes.json` file.

## Documentation

### Creating MoonWalker JSON API.

- **Method One - MoonWalker CLI**

```
$ npm i -g create-moonwalker-app

$ create-moonwalker-app create-api <directory-name>
```

- **Method Two - Clone Github Repository**

- [ ] [gh (GitHub CLI)](https://cli.github.com)

```
gh repo clone MoonWalkerHTTP/moonwalker-json-api-template <directory-name>
```

- [ ] [git](https://git-scm.com/)

```
git clone https://github.com/MoonWalkerHTTP/moonwalker-json-api-template.git <directory-name>
```

### Starting MoonWalker JSON API. 

Production Server - 
```
npm start
```

Development Server - 
```
npm run dev
```

### Port 

The default port for a MoonWalker JSON API is 5000. <br>

To change the Default Port, Open `/config/serverConfig.json` and edit the value for `port`.

### Deployment / Hosting (On a VPS)

MoonWalker JSON APIs can be deployed on many platforms such as [DigitalOcean](https://www.digitalocean.com/) and [Linode](https://www.linode.com/) as it is bascically a [Node.js](https://nodejs.org) Project.

### Slash Route (JavaScript)
After Starting the Development Server, visit [localhost:5000](http://localhost:5000) on your Web Browser.

After the page loads up, You will see a basic `Hello World` JSON Response. This is the `index` route. 

For Editing the Index Route, Open the Directory in your preffered Code editor and open the `app` directory. There you will see a folder / directory named `index` open it and you will see an `index.js` file. 

For Editing the Response, You can edit the `constant` `response` which is an object and the changes will show upon refreshing. 

### `/jsonExample` Route (JSON)
In the MoonWalker JSON API, You have 2 options to respond to a request, You can either use `JSON` or use `JavaScript` for advanced responses. 

The `/jsonExample` Route is written in JSON. 

You can edit the File and the changes will show upon refreshing. 

### Creating a New Route.













