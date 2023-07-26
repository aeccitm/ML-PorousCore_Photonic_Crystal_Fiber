The proposed database for this study will contain information on the optical properties of porous-core THz waveguides, obtained through an innovative approach combining machine learning (ML) techniques and numerical simulations. 

The database will contain the following fields:

## 1. Identifier: ##
- A unique identifier for each porous-core THz waveguide sample.

##  2. Geometric parameters: ## 
 - $d_{2}$: Diameter of the porous core of the waveguide. 
 - $\Lambda_{s}$: Period of the periodic structure in the waveguide.
 - $F$: Porosity of the waveguide. 

##  3. Optical properties: ## 
- $n_{eff}$: Effective refractive index of the THz waveguide.
 - $A_{eff}$: Effective area of the THz waveguide. Dispersion: THz waveguide dispersion values. 
  - Losses: THz waveguide loss values. 

## 4. Materials and operating frequency: ## 
- Porous core material: The material used in the porous core of the waveguide. 

----------

The labeled data required for training the network were generated through numerical simulations using Comsol Multiphysics 5.1 software. These data will be used to train a Multilayer Perceptron (MLP) model with the goal of predicting the optical properties ($n_{eff}$, $A_{eff}$, dispersion and loss) of porous-core THz waveguides. 

This database will allow scientists and researchers to access detailed information about the optical properties of the porous-core THz waveguides shown in Figure and use it to optimize the design of these waveguides and related optical devices. In addition, continued expansion and optimization of the database is expected to further improve the performance of the ML model and accelerate the design of future PCFs and optical devices based on THz waveguides.

![Cross-section view of the proposed porous-core THz waveguide. The inset shows the enlarged view of the porous- core][https://files.osf.io/v1/resources/269zn/providers/osfstorage/64ae1795cdab330502de4e0b?mode=render]
