# Izhikevich Live Script

This Live Script simulates the Izhikevich model for spiking neurons using MATLAB code in the form of a Live Script. Links to the original paper and the book Dynamical Systems in Neuroscience are provided in the Live Script. The Live Script is accompanied by an App which can be used to generate a Standalone or Web App to share with those without a MATLAB license.

The Live Script demonstrates the spiking response of a neuron having certain membrane properties in response to the injection of an external current pulse. The user can modify the parameters. The first group of parameters deals with membrane parameters, whereas the second group changes the amplitude and width of the current pulse. 

The differential equations defining the Izhikevich model are solved by two methods 
1) with the forward Euler method, using a for loop
2) using the in-built MATLAB ode solver (requires Symbolic Math Toolbox)
The user can choose between the two using a Live Control (drop down menu)

To run this Live Script check if you have a MATLAB license from your school or university. If not, you can download a free trial for 30 days.


