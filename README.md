# notebook_tutorials

## Setup

- Ubuntu 18.04.3 LTS (bionic)
- Python 3.8
- PyTorch 1.10.0 
- Cuda 10.1 #optional
- cudnn7.6.4 #optional

### These same steps work on MacOS as well

```console
you@you:/path/to/folder$ pip3 install virtualenv

you@you:/path/to/folder$ virtualenv venv --python=python3.8

you@you:/path/to/folder$ source venv/bin/activate

(venv) you@you:/path/to/folder$ pip3 install -r requirements.txt

(venv) you@you:/path/to/folder$ ipython kernel install --user --name=<insert name of your venv>

(venv) you@you:/path/to/folder$ jupyter notebook
```

if you add additional dependencies, you can make them explicit by updating the requirements.txt file

```console
you@you:/path/to/folder$ pip3 freeze > requirements.txt
```


$$
\frac{e^{P(True)}}{e^{P(True)} + e^{P(False)}}
$$
