# DataLoader mongoose

## Synopsis

Default mongoose loader for Facebook dataloader https://github.com/facebook/dataloader

## Code Example

```
const { dataLoaderMongoose } = require('dataloader-mongoose');

const shipDefaultLoader = new DataLoader(ids => dataLoaderMongoose(mongoose.model('Ship'), ids));

```

## Installation

```
npm install mongoose dataloader dataloader-mongoose
```

## Tests

TODO: add some tests

## License

Graphql relay mongoose is released under the [MIT License](https://opensource.org/licenses/MIT).
