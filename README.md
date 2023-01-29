# Open API Specification

After reading the [OpenAPI Specification Explained](https://oai.github.io/Documentation/specification.html) series, I want to recreate the Tic-Tac-Toe API specification that the guide builds up throughout the pages.

`openapi.yaml` is going to be our root OpenAPI Document

### Tooling

We use [vacuum](https://quobix.com/vacuum/) that was built in GoLang as OpenAPI linter.

Run the following command for linting your OpenAPI Spec (where `-d` means detailed result)

```
$ vacuum lint -d tic-tac-toe/openapi.yaml
```

Run the following command for a CLI Dashboard:

```
$ vacuum dashboard tic-tac-toe/openapi.yaml
```

Run the following command for an HTML Page Report:

```
$ vacuum html-report tic-tac-toe/openapi.yaml
```
