# opery-sequelize-base-service

> Sequelize base service for opery

## Description

This service adds base methods for all models.

## Requirements

- You need some Sequelize Model to use this service.

## Installation

```bash
npm install --save opery-sequelize-base-service
```

## Methods

### db.models.SomeModel

#### `create(data: Object, options: Object) => Promise<SomeModelInstance>`
#### `findOne(id: Number, options: Object) => Promise<SomeModelInstance>`
#### `findAll(options: Object) => Promise<[SomeModelInstance]>`
#### `update(id: Number, data: Object options: Object) => Promise<SomeModelInstance>`
#### `delete(id: Number, options: Object) => Promise<Object>`
`

## License

MIT © [Guillermo Lopez](http://www.guillermolopez.net)