# Third-Party Attributions --- Jumati

This document lists third-party packages declared as direct dependencies
of the Jumati Node.js application, based on the supplied `package.json`
and `package-lock.json`.

> **Scope:** direct dependencies only. Versions below are the versions
> resolved in the supplied `package-lock.json`.
>
> This file is informational and is not a substitute for the license
> files distributed with each package. Where package metadata was
> incomplete, the license was checked against the package's npm/project
> information rather than guessed.

  Package             Version License
  ----------------- --------- --------------
  bcrypt                6.0.0 MIT
  body-parser          1.20.8 MIT
  cookie-parser         1.4.7 MIT
  dotenv               17.4.2 BSD-2-Clause
  ejs                  3.1.10 Apache-2.0
  express              4.22.2 MIT
  express-flash         0.0.2 MIT
  express-session      1.19.0 MIT
  json                 11.0.0 MIT\*
  jsonwebtoken          9.0.2 MIT
  knex                  2.5.1 MIT
  lodash               4.18.1 MIT
  mysql                2.18.1 MIT
  mysql2               3.24.4 MIT
  nodemon               3.0.1 MIT
  sqlite3               5.1.7 BSD-3-Clause
  token                 0.1.0 BSD-3-Clause
  util                 0.12.5 MIT
  web                   0.0.2 MIT

## Notes

### json 11.0.0

The npm package page currently displays `License: none` in its package
sidebar, while the package README explicitly states that the project is
MIT licensed and refers to its `LICENSE.txt`. Because those two pieces
of npm-hosted metadata conflict, this entry is marked with an asterisk
rather than silently treating the metadata as unambiguous.

Source: https://www.npmjs.com/package/json

### express-flash 0.0.2

The package README contains the MIT License and identifies the copyright
holder as:

`Copyright (c) 2012 RGBboy <me@rgbboy.com>`

Source: https://www.npmjs.com/package/express-flash

### token 0.1.0

The npm package page identifies version 0.1.0 as BSD-3-Clause.

Source: https://www.npmjs.com/package/token

## License references

The authoritative license terms remain those shipped by or published for
each respective project. Package/project pages used for verification
include:

-   bcrypt --- https://www.npmjs.com/package/bcrypt
-   body-parser --- https://www.npmjs.com/package/body-parser
-   cookie-parser --- https://www.npmjs.com/package/cookie-parser
-   dotenv --- https://www.npmjs.com/package/dotenv
-   ejs --- https://www.npmjs.com/package/ejs
-   express --- https://www.npmjs.com/package/express
-   express-flash --- https://www.npmjs.com/package/express-flash
-   express-session --- https://www.npmjs.com/package/express-session
-   json --- https://www.npmjs.com/package/json
-   jsonwebtoken --- https://www.npmjs.com/package/jsonwebtoken
-   knex --- https://www.npmjs.com/package/knex
-   lodash --- https://www.npmjs.com/package/lodash
-   mysql --- https://www.npmjs.com/package/mysql
-   mysql2 --- https://www.npmjs.com/package/mysql2
-   nodemon --- https://www.npmjs.com/package/nodemon
-   sqlite3 --- https://www.npmjs.com/package/sqlite3
-   token --- https://www.npmjs.com/package/token
-   util --- https://www.npmjs.com/package/util
-   web --- https://www.npmjs.com/package/web

------------------------------------------------------------------------

Jumati does not claim ownership of the third-party software listed
above. All trademarks, copyrights, and other rights belong to their
respective owners.
