# Standard File Server, Go Implementation

Golang implementation of the [Standard File](https://standardfile.org/) protocol.


### Running your own server
You can run your own Standard File server, and use it with any SF compatible client (like Standard Notes).
This allows you to have 100% control of your data.
This server implementation is built with Go and can be deployed in seconds.

#### Getting started

**Requirements**

- Go 1.7.5+
- SQLite3 database

**Instructions**

1. Initialize project:

```
  go install github.com/tectiv3/standardfile
```

2. Start the server:

```
standardfile
```

3. Stop the server:

```
standardfile -s stop
```

### Environment variables

**SECRET_KEY_BASE**

JWT secret key

## Contributing
Contributions are encouraged and welcome. Currently outstanding items:

- Test suite

## License

Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html
