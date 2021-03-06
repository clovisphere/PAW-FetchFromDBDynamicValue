# PAW-FetchFromDBDynamicValue

A [Paw](https://paw.cloud/) extension to fetch value from a database (currently limited to [MySQL](https://www.mysql.com/)).

![Extension](screenshot/ext.png)


**Important Note:**
> I still need to figure out and fix the "Cannot find module 'mysql2'" error. My guess is PAW's extensions use 'target': 'web', and this limit the use of backend related modules/packages...

![error](screenshot/error.png)


#### Prerequisites

```
nvm install
nvm use
npm install
```

#### Build

```
npm run build
```

#### Install

```
make install
```

#### Test

```
npm test
```

### License

This Paw Extension is released under the [MIT License](https://www.wikiwand.com/en/MIT_License). Feel free to fork, and modify!

Copyright © 2018, Clovis Mugaruka
