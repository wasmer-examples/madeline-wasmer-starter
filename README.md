This is a simple [Madeline](https://docs.madelineproto.xyz/) application starter

## Getting Started

Modify the logic of your the PHP application in the `app/index.php` file.

<!-- First, install the dependencies with composer:

```
$ composer install
``` -->

You can run things locally with:

```
$ php -t app -S localhost:8080
```

Or you can also use `wasmer run` to run it locally (check out the [Wasmer install guide](https://docs.wasmer.io/install)):

```console
$ wasmer run .
```

Open [http://localhost:8080](http://localhost:8080) with your browser to see the result.


## Deploy on Wasmer Edge

The easiest way to deploy your PHP app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: TODO

Run this commmand to deploy to Wasmer Edge:

```bash
wasmer deploy
```