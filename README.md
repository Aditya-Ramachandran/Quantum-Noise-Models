<a href="https://www.python.org/" rel="nofollow"><img src="https://camo.githubusercontent.com/5392ad6fb7875a2520001270f08309896b6cb25d/687474703a2f2f466f7254686542616467652e636f6d2f696d616765732f6261646765732f6d6164652d776974682d707974686f6e2e737667" alt="forthebadge made-with-python" data-canonical-src="http://ForTheBadge.com/images/badges/made-with-python.svg" style="max-width:100%;"></a>

<a href="https://www.python.org/downloads/release/python-360/" rel="nofollow"><img src="https://camo.githubusercontent.com/87f2b188d841044a9df21639ec855d6bcc937343/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e2d332e362d7465616c2e737667" alt="Python 3.6" data-canonical-src="https://img.shields.io/badge/python-3.6-teal.svg" style="max-width:100%;"></a>       <a href="https://github.com/Naereen/StrapDown.js/blob/master/LICENSE"><img src="https://camo.githubusercontent.com/16ffa88a35d0857d4db701c510eb3099fbf8d907/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f4e61657265656e2f5374726170446f776e2e6a732e737667" alt="GitHub license" data-canonical-src="https://img.shields.io/github/license/Naereen/StrapDown.js.svg" style="max-width:100%;"></a>
# Quantum-Noise-Models

Building a noise model for simulating a Qiskit quantum circuit in the presence of errors. We know that the simulator always imitates an ideal Quantum Computer so when we run a circuit on it, it won't show any noise (Quantum Noise) and always gives us the exact expected result with any moise. But the quantum computers we have today are way too noisy and are not at all ideal. So I made this so when you run your circuit on a simulator, an approximate *NoiseModel* can be generated automatically from the properties of real device backends from the IBMQ provider using the *from_backend()* method.
Then I also coded a custom noise model using some pre-defined quantum error functions in the *NoiseModel* class (the Depolarizing Noise Model) and it we deliberately add errors in it and then plot the final results in the form of a histogram.

## Softwares and Libraries used
- Jupyter Notebook
- Matplotlib
- Qiskit
  1. qiskit-terra 
  2. qiskit-aer
  3. qiskit-ibmq-provider
  
