# Video Games data analysis
## Analysis includes:
* Preprocessing
* Descriptive analysis
* Statisctical analysis
* Clusterization
* Classification 

## Libraries used:
* NumPy
* SciPy
* Pandas
* Scikit-learn
* Matplotlib
* Statsmodels

## Virtualenv installation
* Create virtualenv

  <code>$ virtualenv your-venv --no-site-packages</code>

* Activate virtualenv

  <code>$ source your-venv/bin/activate</code>

* Install jupyter in the virtualenv

  <code>(your-venv)$ pip install jupyter</code>

* Add the virtualenv as a jupyter kernel

  <code>(your-venv)$ ipython kernel install --name "your-venv" --user</code>
  
* List available kernels

  <code>(your-venv)$ jupyter kernelspec list</code>
 
* Check if kernel.json file in your kernel directory contains correct path to your virtualenv
 
* You can now select the created kernel your-env when you start Jupyter
