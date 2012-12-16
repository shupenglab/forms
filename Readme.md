# forms

  create forms dynamically by providing a JSON schema

## Installation

    $ component install nickjackson/forms

## Spec
[wiki/Spec](https://github.com/nickjackson/forms/wiki/Spec)


## Todo
* Add component/Model support?
* Add Date/Calendar functionality
* Add Tests
* Validation

## API

### new Form(schema)
Creates new Form object based on schema object
 
### .render()
Renders form
 
### .view
Rendered DOM

### .on('attribute', function(name, params, cb(dom)))
Override a particular attribute by calling the callback with a DOM element

## License

  MIT