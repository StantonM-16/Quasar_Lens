## Quasar_Lens 

Code designed to calculate and graph the Lensing Optical Depth tau_m, Magnification Bias B, and Probability of Lensing prob_lens for a quasar in a flux-limited survey which may or may not be gravitationally lensed.

The graphing feature is designed to graph the chosen dependent variable against any one of the numerical variables the class takes as input, with seperate lines for each specified value of a secondary variable (any remaining variable) to allow for analysis of how variation in multiple variables at once changes the values of the above attributes.

Note that due to the complexities of the above operation, and limitations with the speed of astropy functions, it is not unusual for the tau_m_graph and prob_lens_graph methods to take a while (1-2 minutes) to execute.

Refer to docstrings within the code for more information on each method of the class.

Please direct any queries or bugs found to msstan@student.unimelb.edu.au.


## Acknowledgements

Thanks to Professor Rachel Webster of the University of Melbourne and the Laby Foundation for the opportunity to undertake the project in which this code was written.

The calculations within the code are taken predominantly from equations in Yue et al. 2022, and the default values of the attributes are sourced from the same paper.

Some of the code for the calculation section was also adapted from that written by Minghao Yue for his paper, available at:
https://github.com/yuemh/lensQSOsim/tree/main/analytical.

The inspiration for the structure of the code was taken from code of Samuel Laihei, available at:
https://github.com/samlaihei/BADFit/tree/main.

