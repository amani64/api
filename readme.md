## Restful response package

This package provide you restful json response.

## Documentation

Create Factory class:
`$factory =  app(Factory::class);`

Set custom serializer:

`$factory->transformer()->getAdapter()->setSerializer($serializer);`

In your Controller:

`return $factory->collection($collection, MyTransformer::class, ['identifier'=> 'myData'])`

## License

This package is licensed under the [BSD 3-Clause license](http://opensource.org/licenses/BSD-3-Clause).
