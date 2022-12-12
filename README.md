# README

In this interview you will be pairing with your interviewer to create a Rails JSON API.
The goal of this interview is to assess your architecture, database design,
syntax, and code style. There is no goal to complete a specific task. We will simply use the alotted
time to design and code in the process that you would normally use for _spiking_ a project.

## Before the interivew

The only requirement before beginning the interview is to ensure that you can boot this code base
in a local environment. It's up to you on how you will install ruby, bundler, and postgresql.
After ensuring you have those base tools installed.  You should be able to run the following to setup the project.

```
bundle install
rails db:create db:migrate
```

You will know if the project is installed correctly if you can run `rails server` and see the
rails getting started placeholder page at `http://localhost:3000/`. You should also ensure you can
run `rails test` and see a successful run of the tests (which are empty)

### Customizing the repo

This repo is a freshly generated rails project created with ruby `3.1.2` and running the command:

```
rails new technical-interview --api -d postgresql
```

There is nothing sacred about this code base. Feel free to generate a new project with any settings
you prefer to work with (ie `rspec` or different version or ruby).




