# Q-SITE 2023 - IBM Quantum Mini-challenges

## Requirements

You can run the challenge notebooks in either the IBM Quantum Lab or locally on your own computer.

### Running on IBM Quantum Lab

Go to the IBM Quantum Platform at this link: quantum-computing.ibm.com

You can create a free account to access the IBM Quantum Platform, including open access to real quantum computers!

Once you have an account, navigate from the dashboard to the IBM Quantum Lab. This is an online Python programming envionment running from your Web browser. You'll find that all of the necessary Python packages are pre-installed in the Lab, so no need to install anything yourself!

You can upload the challenge notebooks to the IBM Quantum Lab from the file browser on the left using the Upload icon.

### Running locally

Use Python v3.9 or above. It is suggested that you create a custom Python environment using either `conda` or `virtualenv`, then activate the environment before installing the needed Python packages.

Install the following Python packages using the `pip` command:

```
qiskit
qiskit-aer
matplotlib
pylatexenc
jupyter [or jupyterlab]
```

You can install all of the needed packages by using the included `requirements.txt` file.

The notebook will be run using the circuit simulators in Qiskit Aer. If you would like to run the code on real quantum hardware, note that you'll need to create a free account with the IBM Quantum Platform here: quantum-computing.ibm.com. Once you have an account, you will need to get your API token from the dashboard of the IBM Quantum Platform and use it when initializing the IBM Quantum service. Use these instructions: https://qiskit.org/ecosystem/ibm-provider/tutorials/1_the_ibm_quantum_account.html