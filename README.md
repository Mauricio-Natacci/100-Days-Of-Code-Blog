# Blog

Using MySQL in NodeJS & Express websites

## Installation

npm install to install dependencies

```bash
npm install
```

You need to create a file called "database.js" inside the folder "data" at the project root

```bash
const mysql = require('mysql2');

const pool = mysql.createPool({
   host: 'localhost',
   database: 'name',
   user: 'user',
   password: 'password'
});

module.exports = pool;


```

## Contributing

Pull requests are welcome

## License

[MIT](https://choosealicense.com/licenses/mit/)
