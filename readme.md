# Hydrator
Simple to use hydrator to hydrate an object from array or extract an object to an array.

## Usage
To install the hydrator use the following command;
```
composer require onemustcode/hydrator
```

### Hydrating
To hydrate an object you can use the hydrate method;
```php
$object = new Object(); // The object to hydrate
$data = ['some_field' => 'some_value', 'boolean_field' => true];
$object = $hydrator->hydrate($object, $data);
```

### Extracting
To extract an object to an array you can use the extract method;
```php
$array = $hydrator->extract($object);
```

### Todo
- Add strategies
- Add unit tests