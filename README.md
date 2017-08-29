# QuizApiDocs
## Synopsis

Documentation for the development team of Beyond Finance Server will be saved and updated here.

These files can be used with [Postman](https://www.getpostman.com/).

For the time being this is only a reference, and the calls will only work with the correct database setup.

## The Basics

Postman allows using variables in http requests and tests. This is very useful for shared work.

For example a simple request will look like this inside postman:

```
{{protocol}}://{{server}}/api/v1/cms/leads
```

- Protocol stands for **http** or **https**
- RoR localhost servers are usually **localhost:3000** (notice this includes the port)

## How to use

1. **Import** the collection files to postman
2. **Import** the environment files to postman
3. **Import** the global variable file to postman

- **Change** the **values** (not names) of localhost environment variables to suit your localhost settings
- **Change** the **values** (not names) global variables if they exist and if you know what you are doing
- **Do Not** change any other environment files

## How to contribute

For all exports please use **Collection V2**.

1. **Export** the collection files you updated from postman
2. **Export** your global variables from postman
3. **Add** the files to the repo directory
4. **Commit**
5. **Push**

**Do Not!!!** export your environment files from postman.

All new requests must you environment variables where appropriate.

## To do

1. Add a collection for testing
2. Create mocks for front end teams
