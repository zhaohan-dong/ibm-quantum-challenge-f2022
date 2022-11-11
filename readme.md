# IBM Quantum Computing Challenge Fall 2022 - Zhaohan Dong
This repository hosts my submission for the IBM Quantum Computing Challenge 2022. The original repository is at https://github.com/qiskit-community/ibm-quantum-challenge-fall-22 <br />

The python environment was configured with `python 3.10.8` and `pip 22.3.1`. `qiskit-terra`, `qiskit-ibm-runtime`, `qiskit-nature`, `qiskit-optimization` and `prototype-zne` installed using `pip install qiskit\[all]`. `matplotlib`, `numpy` and `pandas` were included in installation. For details, please refer to `requirements.txt`.

To run grader, qc grader is installed using `pip install git+https://github.com/qiskit-community/Quantum-Challenge-Grader.git`. Variables set using `%env QXToken=YOUR_IBM_QUANTUM_TOKEN \n %env QC_GRADING_ENDPOINT=https://qac-grading.quantum-computing.ibm.com \n %env QXAuthURL=https://auth.quantum-computing.ibm.com/api`

IBM Quantum requires API, the credential is not uploaded. It's accessed from file `content/ibm-quantum-token.json` with format `{ "token": "MY_IBM_CLOUD_API_KEY"}`.