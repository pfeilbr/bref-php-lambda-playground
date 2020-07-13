# bref-php-lambda-playground

learn [bref](https://bref.sh/), deploy and run serverless PHP applications

## Prerequisites

* [PHP](https://www.php.net/)
* [serverless framework](https://www.serverless.com/)

## Running

```sh
# install
composer require bref/bref

# init
vendor/bin/bref init

# edit `index.php`

# deploy
serverless deploy

# test / invoke
serverless invoke -f "function"

# test / invoke with event data
serverless invoke --function "function" --data '{"name": "foo"}'
```

## Resources

* [bref | Installation](https://bref.sh/docs/installation.html)