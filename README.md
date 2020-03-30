# trip-let

A simple command-line application to build Trip-lets.

![Trip-let](images/BEG.jpg "A Trip-let built with this code")

A trip-let is a three-dimensional solid that, when projected along three
perpendicular axes, produces three letters of the alphabet (or, in general, any
other shape). They were popularized in the famous Hofstadter's book _Gödel,
Escher, Bach: An Eternal Golden Braid_.

This application produces a trip-let given its three projections.

## Example

```sh
trip-let -x data/B.png -y data/E.png -z data/G.png -o BEG.obj --find-best-transform
```

![trip-let](images/example.png "Example")

## Installation

```sh
# Clone the repository
git clone https://github.com/pmneila/trip-let.git

# Install requirements (PyMCubes)
pip install -r requirements.txt

# Install
cd trip-let
python setup.py install
```

Uninstall with
```sh
pip uninstall trip-let
```
