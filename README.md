## Ruby on Rails Microblogging App

Microblogger is a practice app built in Rails using the sample app from the [Ruby on Rails Tutorial](http://railstutorial.org/) by [Michael Hartl](http://www.michaelhartl.com/).

## Modifications

There are several aspects that I modified or completely changed, including:

* first change

## License

All source code in `Microblogger` is available jointly under the MIT License and the Scotchware License, as well as the original licenses provided by `Michael Hartl`.  See [LICENSE.md](LICENSE.md) for details.

## Getting started
To get started with the app, clone the repo and then install the needed gems:
```
$ bundle
```
Next, create & migrate the database:

```
$ rails db:create

$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rake
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).
