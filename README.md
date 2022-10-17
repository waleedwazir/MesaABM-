# MesaABM-
### Installing Python
To start, install Python. but make sure your environment is set up with Python 3. Mesa requires Python3 and does not work in Python 2 environments.
You can install python at this link https://www.python.org/downloads/, Make sure to **tick add to Path** when running the setup.exe file

### Installing Mesa
Run the following commands in **CMD** after installing python

`$ pip install mesa`

When you do that, it will install Mesa itself, as well as any dependencies that aren’t in your setup yet. Additional dependencies are required to run this tutorial, which can be installed directly from github repository by running the command below in **CMD**:

`$ pip install -r https://raw.githubusercontent.com/projectmesa/mesa/main/examples/boltzmann_wealth_model/requirements.txt`
