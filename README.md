# Sample Application with Erlang

This sample is running on: https://erlang.is-easy-on-scalingo.com/

## Deploy via Git

Create an application on https://scalingo.com, then:

```shell
scalingo -a my-app git-setup
git push scalingo master
```

And that's it!

The application is running at this url: https://sample-erlang.osc-fr1.scalingo.io/

## Deploy via One-Click

[![Deploy to Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.scalingo.com/deploy)

## Running Locally

First, you need to have a working Erlang environment.

### Compile and Execute

```shell
make run
```

The app listens by default on the port 8080 or the one defined in the `PORT`
environment variable.
