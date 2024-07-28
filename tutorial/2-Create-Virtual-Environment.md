# Create A Virtual Envoronment

It is recommend setting up your development environment using a manager like `venv`, which creates isolated python environments. Other environment managers, like 
- [virtualenv](https://virtualenv.pypa.io/en/latest/)
- [pipenv](https://pipenv.pypa.io/en/latest/)
- [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/), 
- [hatch](https://hatch.pypa.io/latest/) 
- [poetry](https://python-poetry.org)

are available and will likely work, but will have different syntax to the syntax shown here. 

Our packages are set up using `virtualenv` with `pip`  

Run the following command to create a new virtual environment in the `venv` directory

```shell
python3 -m "venv" "venv" 
```

You can specify the Python version when creating a virtual environment. For example, run the following command to specify Python 3.11 for the virtual environment. 
 ```shell
python3.11 -m "venv" "venv311" 
```

Activate it by running
```shell
source "venv311/bin/activate"
```

[3-Create-Template](./3-Create-Template.md)