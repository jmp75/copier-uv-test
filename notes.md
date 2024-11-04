# copier-uv-test

Trial copier-uv as a template for py packaging

https://pawamoy.github.io/copier-uv/requirements/

I ahve installed pipx, so giving a try to `pipx install copier`

'copier' already seems to be installed. Not modifying existing installation in '/home/blah/.local/share/pipx/venvs/copier'. Pass '--force' to force installation.

`pipx upgrade copier` then

`which copier` returns something

```sh
# IMPORTANT NOTE: you need to specify the containing folder, not /src hoping it will create the directory for you from the project name!!
copier copy --trust "gh:pawamoy/copier-uv" $HOME/src/copier-uv-test
```

`copier-uv-test` and description. Other settings have defaults from, probably, git creds.

`direnv allow`

`export PYTHON_VERSIONS="3.11"` added to `.envrc`