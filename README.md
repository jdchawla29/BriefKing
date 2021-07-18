# BriefKing

### Key Dependencies

Following versions of python have to be installed on the machine 

* python 3.9.2
* pip 21.0.1

Other requirements

Download models from
* https://drive.google.com/file/d/1-3EpW1EzpB2TrvCSjyA0LjjdOzkl5NSx/view?usp=sharing
* https://drive.google.com/file/d/1-HiRlzexw6Kk1ub1MPFWtSy89XRPrKUq/view?usp=sharing
 
and add to the directory you'll work with. 

### Steps to Run

Open the terminal at directory where you want to clone the project

```
git clone https://github.com/jdchawal29/BriefKing.git
cd BriefKing
```

Setup virtual environment

```
pip install virtualenv
virtualenv venv
```

To activate corresponding environment, on Linux / OS X, use the following

```
source venv/bin/activate
```

On Windows, following can be used

```
venv\scripts\activate
```

When virtual envirnoment is activated, install the requirments
```
pip install -r requirements.txt
```

To run the web application, do the following
```
streamlit run BriefKing.py
```

Deactivate the virtual environment by using following command on terminal
```
deactivate
```