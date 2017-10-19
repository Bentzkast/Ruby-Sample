# Ruby on Rails Tutorial sample application

This is the sample application for Learning

## License

All source code in the available under the MIT License

## Getting Started

To get started with the a app, clone the repo and then install the needed gems:
```
$ bundle install --without production
```

Next, migrate the Database:
```
$ rails db:migrate
```

Finally, run the test suite to verity that everything is working correctly
```
$ rails test
```

If the test suite passes, you will be ready to run the app in a local server:
```
$ rails server
```
