number: 20 # leave as-is, maintainers will adjust 
title: Closed loop optimization of hydrogel formulations using dynamic light scattering 
topic: real-world

team_leads: 
  - Owen Melville (@owen-melville) (Acceleration Consortium) 

# Comment these lines by prepending the pound symbol (#) to each line to hide these elements
contributors:
  - Ilya Yakavets (@yakavetsiv) (Acceleration Consortium) 
  - Jeff Watchorn (@jwatchorn)(Acceleration Consortium) 
  - Yimu Zhao (Acceleration Consortium) 
  - Nipun Gupta (Acceleration Consortium) 

# github: AC-BO-Hackathon/project-project-20-optimystics
# youtube_video: https://youtu.be/Qbvq7uolQr8?si=BQBLDr9OtOTi1JLS
--- 

Hydrogels are hydrophilic crosslinked polymer networks used for cell culture, drug delivery, agriculture and tissue engineering. Depending on the application (eg 3D printing or injection), hydrogels require different mechanical and rheological properties, with companies such as Millipore-Sigma already selling hydrogels with custom stiffness. The hydrogel formulation - usually water, polymer and crosslinking agent along with other additives - can markedly affect gelation. This limits the ability of researchers to easily modify formulation components, for example by adding biologically relevant functional groups to the polymer. Their new formulation, if it even gels, will likely not have the target properties. Thus, a self-driving lab could be used to optimize gel formation and properties for a new formulation with a specific application in mind such as injections or cell cultures. Unfortunately, the automated processing of soft, fragile hydrogels can be a challenge. Also, the established techniques for monitoring gelation, such as imaging-based microrheology, are data-intensive and finicky. Thus we propose using dynamic light scattering (DLS), which can be performed in a plate reader, to monitor gelation in a 96-well plate. The concentrations of various components along with the crosslinking parameters can be varied using Bayesian optimization to find the hydrogel formulation with the target mechanical and rheological properties as measured indirectly using DLS. 

References: 
1. Xu et al. (2020). [High-Throughput Synthesis, Analysis, and Optimization of Injectable Hydrogels for Protein Delivery](https://doi.org/10.1021/acs.biomac.9b01132). Biomacromolecules 

2. Krajina et al. (2017). [Dynamic Light Scattering Microrheology Reveals Multiscale Viscoelasticity of Polymer Gels and Precious Biological Materials](https://doi.org/10.1021/acscentsci.7b00449). ACS Central Science 
