[![Build Status](https://travis-ci.org/hadim/pygraphml.svg?branch=master)](https://travis-ci.org/hadim/pygraphml)

# pygraphml

`pygraphml` is a small Python library designed to parse GraphML file. To
see specification about GraphML, see http://graphml.graphdrawing.org/

Documentation and tutorial are available at http://hadim.github.io/pygraphml/. A notebook is also available [here](example.ipynb).

# Requirements

- Python > 2.7 and > 3.3
- NetworkX (http://networkx.lanl.gov/): only for the visualization

# Install

`pip install pygraphml`

# License

Under BSD license. See [LICENSE](LICENSE).

# Authors

- Hadrien Mary <hadrien.mary@gmail.com>
- Nick Hamilton <n.hamilton@imb.uq.edu.au>

# How to release a new version

- Modify version number in `pygraphml/__init__.py`
- Commit and push changes
- Make Github release
- Create packages : `python setup.py sdist bdist_wheel`
- Upload packages : `twine upload dist/*`
