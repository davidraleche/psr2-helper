
### PSR-2 Code Styling

`vendor/bin/phpcs --standard=PSR2  app src`

`vendor/bin/phpcbf --standard=PSR2 --report=json app src`

`vendor/bin/phpunit`

`vendor/bin/phpunit --log-junit web/phpunit/phpunit.xml --coverage-clover web/phpunit/coverage.xml --coverage-html web/phpunit/`

Generate swagger documentation Swagger endpoint

`vendor/bin/openapi -o "web/swagger.json" app/ src/ web/`
