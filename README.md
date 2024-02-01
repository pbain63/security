# Authentication

Various versions of APP's security and authentication.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
npm install 
```

## Usage

```python
require("dotenv").config();
const express = require("express");
const bodyParser = require("body-parser");
const ejs = require("ejs");
const mongoose = require("mongoose");
const session = require("express-session");
const passport = require("passport");
const passportLocalMongoose = require("passport-local-mongoose");
const GoogleStrategy = require("passport-google-oauth20").Strategy;
const findOrCreate = require("mongoose-findorcreate");
```
## Technology
CSS4, Node.js, Express.js, EJS, Mongoose, passport-google-oauth20

## Dependencies
"bcrypt",
    "body-parser",
    "dotenv", 
    "ejs",
    "express",
    "express-session",
    "md5",
    "mongoose",
    "mongoose-encryption",
    "mongoose-findorcreate",
    "passport", 
    "passport-google-oauth20", 
    "passport-local",
    "passport-local-mongoose"

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
