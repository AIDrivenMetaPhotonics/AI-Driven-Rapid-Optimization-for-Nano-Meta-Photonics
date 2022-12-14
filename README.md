# AI-Driven-Rapid-Optimization-for-Nano-Meta-Photonics
This is a unique meta-absorber dataset containing 10,400 samples collected via commercial EM software i.e., CST Microwave Studio.  This dataset is collected and employed for the forward and inverse design models presented in the work "AI-Driven Rapid Optimization for Nano-Meta-Photonics".

Meta-atom_images.zip: contains the inputs which are in the form of 64 x 64 rgb images of 3D meta-atoms having various shapes and made of different materials (indicated by the colour of the nano-resonator). 


Input_complete.csv:  contains the second input which is in the form of [3 x 1] vectors having 1 dimensioanl input parameters of the meta-atom including its subtrate’s height (hs), resonator’s height (hp) and period (P).


Output.csv: The outputs are [500x1] vectors which are the absorption spectrums over the broadband wavelength range (300nm-1200nm) to cover the optical domain of the EM spectrum. The role of these inputs and outputs is reversed for inverse design model.


These meta-atoms are made up of eight (8) different materials ranging from plasmonics to refractory materials with 4 different shapes. The example materials include gold (Au), Silver (Ag), Chromium (Cr), Molybdenum (Mo), Nickel (Ni), Tantalum (Ta), Titanium Nitride (TiN) and Zirconium Nitre (ZrN).Further details about the dataset and the models implemented on it is given in the research paper “AI-Driven Rapid Optimization for Nano-Meta-Photonics”.
