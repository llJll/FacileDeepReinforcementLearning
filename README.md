Chapter0 Get started
===========

Choice of environment
-----------------------

[Stable baselines](https://readthedocs.org/projects/stable-baselines/downloads/pdf/master/) is recommended as a improvement of OpenAI-baselines.


Setup
-----

- Before starting, using Virtual Environment is highly recommended.
- Note: Baselines requires python3 (>=3.5)

### Preparation of Virtual Environment (VENV) and Python3
Please refer the complete [guide](https://docs.python-guide.org/starting/installation/).

#### Here is an example using virtualenv and default interpreter python2.7 under Mac OSX

Install python3 by homebrew, which doesn't affet system python.

`brew install python3`

Create a virtual environmet named python3 under `{your_folder}/virtualenv`

`virtualenv -p /usr/local/bin/python3 python3`

activate the virtual environmet

`. bin/activate `

install needed packages under VENV
**Note**: Stabe-Baselines supports Tensorflow versions from **1.8.0 to 1.14.0**. Support for Tensorflow 2 API is planned.

```
sudo chown -R $(whoami) $(brew --prefix)/*
brew install cmake openmpi
pip install stable-baselines[mpi]`
pip install tensorflow
```

### (optional) loading virtual environment in VSCode 
If you hope to load virtual environment in VSCode editor, set in settings.json as below:
`"python.venvPath": "~/Codes/virtualenv"` 


Hello, world!
--
```
```

Chapter1
========

References
==========

Essential Papers
----------------

Links
-----

More resources
--------------

http://rail.eecs.berkeley.edu/deeprlcourse/
