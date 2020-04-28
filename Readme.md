## Getting started
1. Create a working directory
```
$ mkdir <work-directory>
$ cd <work-directory>
```
## Create a virtual environment
2. Copy the requirements.txt file and all of the remaining files into your working directory. Then create a virtual environment by running the following commands
```
$ python3 -m venv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```
To access the jupyter notebooks run the following command

```
$ jupyter notebook
```
then you can access the source code neural_net.ipynb notebook. The model weights are saved and then loaded into the test_net.ipynb notebook (contain trained model). The file how_ping_works.pdf contain information about the architecture of the model and other answered questions regarding the model.