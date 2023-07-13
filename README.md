# ruby-blog
A simple blog website made withh Ruby on Rails.

## Setting up prerequisites

First make sure you have all the dependencies.

Run the following command to check if you have Ruby 2.7.0 or greater installed.

```console
$ ruby --version
ruby 2.7.0
```

You can download Ruby for your operating system [here](https://www.ruby-lang.org/en/documentation/installation/).


Run the following command to check if you have SQLite3 3.0.0 or greater installed.

```console
$ sqlite3 --version
3.40.1 2022-12-28 14:03:47 df5c253c0b3dd24916e4ec7cf77d3db5294cc9fd45ae7b9c5e82ad8197f3alt1
```

You can download SQLite3 for your operating system [here](https://www.sqlite.org/download.html).

If you have all dependencies, install Rails with the following command:

```console
$ sudo gem install rails
```

Afterward, check to see if you have Rails installed, anything equals or greater than 7.0.0 should suffice.

```console
$ rails --version
Rails 7.0.5
```

You should be good to go now.

## Running the application

Clone this repo locally on your machine, go the its root directory, and run:

```console
$ rails server
```
If everything worked correctlym you should see something like this on you terminal:

```console
=> Booting Puma
=> Rails 7.0.5 application starting in development 
=> Run `bin/rails server --help` for more startup options
Puma starting in single mode...
* Puma version: 5.6.5 (ruby 3.2.2-p53) ("Birdie's Version")
*  Min threads: 5
*  Max threads: 5
*  Environment: development
*          PID: 46479
* Listening on http://127.0.0.1:3000
* Listening on http://[::1]:3000
Use Ctrl-C to stop
```

Open localhost:3000 on your browser, and it should be working. You can now post your cool blogs Yay!!!
