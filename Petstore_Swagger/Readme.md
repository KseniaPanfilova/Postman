# Testing of Petstore Swagger open API

**Source - [https://petstore.swagger.io/](https://petstore.swagger.io/)**

The Tests collection consists of CRUD checks for USER entity.

The Environment variables are randomly generated.

## Running the Collection with Newman

To run the Tests collection with Newman you need implement following steps:

- ### Newman installation

Before installation, make sure that `Node.js` and `npm` are installed on your computer.

Then open the CLI and enter the following command:

```sh
npm install -g newman
```

- ### Running the Tests collection

1. Download the Tests collection and the Environment files on your computer.
2. Open the CLI and go to the directory with downloaded files.
3. Enter the command:
```sh
newman run <the Test collection> -e <the Environment>
```
4. Enjoy the process &#128521;
