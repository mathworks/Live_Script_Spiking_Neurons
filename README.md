# Izhikevich Live Script

This project contains a Live Script and two Apps which simulate a well known model for spiking neurons that has been published and is acknowledged. The Live Script is intended as a demo for neuroscience audiences to showcase different Live Script capabilities such as Live Controls, Live Tasks, converting code to local functions, etc.

The Live Script demonstrates the spiking response of a neuron having certain membrane properties in response to the injection of an external current pulse. The user can modify the parameters. The first group of parameters deals with membrane parameters, whereas the second group changes the amplitude and width of the current pulse. 

The differential equations defining the Izhikevich model are solved by two methods 
1) with the forward Euler method, using a for loop
2) using the in-built MATLAB ode solver (requires Symbolic Math Toolbox)

Whereas the forward Euler is the simplest integration method, it is also the least accurate and stable. The user can choose between the two using a Live Control (drop down menu)

The Live Script is accompanied by two Apps, one using the forward Euler method and the other using the MATLAB in-built ode45 to solve the differential equations that define the model. To generate a Standalone App to share with those without a MATLAB license, compile the IzhikevichApp_Euler App.

To run this Live Script check if you have a MATLAB license from your school or university. If not, you can download a free trial for 30 days.

[![View Live_Script_Spiking_Neurons on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/86198-live_script_spiking_neurons)
[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=mathworks/Live_Script_Spiking_Neurons&file=/main/LiveScript_Izhikevich.mlx)
