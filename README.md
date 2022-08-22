# go-forum

[![Build Status](https://travis-ci.org/chrisf15/go-forum.svg?branch=master)](https://travis-ci.org/chrisf15/go-forum)
[![codecov](https://codecov.io/gh/chrisf15/go-forum/branch/master/graph/badge.svg)](https://codecov.io/gh/chrisf15/go-forum)
[![Go Report Card](https://goreportcard.com/badge/github.com/chrisf15/go-forum)](https://goreportcard.com/report/github.com/chrisf15/go-forum)

go-forum is a simple forum web application that uses the `database/sql` and `http` packages in the standard library, with `toml` as the configuration file format and `MySQL` as the database.

## Installation

```bash
git clone https://github.com/chrisf15/go-forum.git
```

Create database:

```bash
mysql -uroot -proot < model/setup.sql
```

Fill in the configuration options in `config.toml`.

Then, build it:

```bash
go build -o go-forum
```

And, run it：

```bash
./go-forum
```

## Usages

Visit `http://localhost:8080/`.

## Contributing

If you feel that there is something to improve this project, please feel free to launch Pull Request.

For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT License](./LICENSE "MIT License")