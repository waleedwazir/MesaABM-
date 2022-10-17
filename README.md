# MesaABM-

The code model is a very simple simulated agent-based economy, drawn from econophysics and presenting a statistical mechanics approach to wealth distribution [Dragulescu2002]. The rules of our tutorial model:

There are some number of agents.

All agents begin with 1 unit of money.

At every step of the model, an agent gives 1 unit of money (if they have it) to some other agent.

Despite its simplicity, this model yields results that are often unexpected to those not familiar with it. For our purposes, it also easily demonstrates Mesa’s core features.

### Installing Python
To start, install Python. but make sure your environment is set up with Python 3. Mesa requires Python3 and does not work in Python 2 environments.
You can install python at this link https://www.python.org/downloads/, Make sure to **tick add to Path** when running the setup.exe file

### Installing Mesa
Run the following commands in **CMD** after installing python

`$ pip install mesa`

When you do that, it will install Mesa itself, as well as any dependencies that aren’t in your setup yet. Additional dependencies are required to run this tutorial, which can be installed directly from github repository by running the command below in **CMD**:

`$ pip install -r https://raw.githubusercontent.com/projectmesa/mesa/main/examples/boltzmann_wealth_model/requirements.txt`

This will install the dependencies listed in the requirements.txt file which are:
- jupyter (Ipython interactive notebook)
- matplotlib (Python’s visualization library)
- mesa (this ABM library – if not installed)
- numpy (Python’s numerical python library)

###Running the Code

To run the code I am using **VScode** which you can download at https://code.visualstudio.com/download.
Make sure to set VScode's interpreter to the version you downloaded at the start of this readme.

You can set the Interpreter by **CTRL+SHIFT+P** then Searching for **Python: Select interpreter** which will then show you the versions of python you have.

You can then Open the Source code folder in VScode, inside the code folder is:
- Main.py(Run this to execute the program)
- MoneyModel.py(Mesa Model)

Run the **Main.py** file in VScode this will execute the Mesa Model.

