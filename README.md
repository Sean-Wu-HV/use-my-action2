# Example Package

For poetry testpypi url use: https://test.pypi.org/legacy/, don't end with simple/

set pypitoken with: `poetry config poetry config pypi-token.testpypi pypi-xxxx`
`poetry config repositories.testpypi https://test.pypi.org/legacy/`

then `poetry publish -r testpypi`