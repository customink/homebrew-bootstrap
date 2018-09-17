# Homebrew Bootstrap
Orginally forked from [`github/homebrew-bootstrap`](https://github.com/github/homebrew-bootstrap), this homebrew tap makes available a command to help get python set up automatically based on a `.python-version` file, and leverages `pipenv` to handle dependency bundling.

- [`brew bootstrap-pyenv-python`](cmd/brew-bootstrap-pyenv-python): Installs Python and Pipenv.

## Usage

```bash
brew tap customink/bootstrap
brew bootstrap-pyenv-python
```
The following should be comitted to your application repo:
* `.python-version` to specify the proper python version.
* `Pipfile` and `Pipfile.lock` for specifying dependency versions.

## Status
In active development.

## Original Author
[@mikemcquaid](https://github.com/mikemcquaid/)

## Forked with ❤️ for Custom Ink's python developers by
[@rypit](https://github.com/rypit/)

## License
Homebrew Bootstrap is licensed under the [MIT License](http://en.wikipedia.org/wiki/MIT_License).
The full license text is available in [LICENSE.txt](https://github.com/github/homebrew-bootstrap/blob/master/LICENSE.txt).
