# comfy-pool-model

This model was made for for a final project in a Modeling & Simulation undergraduate class at Mount Holyoke College. It aims to answer
two questions:

  **Qn. 1)** Between December 2018 and December 2019 (when this project was finished), what were the most comfortable days to go swimming in the average inground, unheated, outdoor pool in South Hadley, MA?
  
  **Qn. 2)** How does a pool's surface area affect such days?
  

## Outline of `Final Project.ipynb`

**1)** The model is first pictured as a stock-and-flow diagram.

**2)** It is then written mathematically in terms of differential equations.

**3)** The basic functions needed to execute the model are written out.

**4)** Three sub-models are created to test the mathematics:
   - The effect of warmer air temperatures on pool water temperature.
   - The effect of warmer air temperatures and sunlight on water temperature.
   - The effect of colder air temperatures on water temperature.
   
**5)** The (main) model for Qn. 1 is made, run, and interpreted.

**6)** The model iteration in Qn.2 is made, run, and interpreted.


## Running
`cd` into the directory containing the downloaded files and run `jupyter notebook`. This should open the jupyter homepage in a browser.
Additionally, NetCDF4 should also be installed (use the command `pip install netCDF4`). This model needs it for libraries that assist with traversing scientific datasets.

Once that is done, you can run all cells in `Final Project.ipynb` and go through the notebook :)

#### Troubleshooting for MacOS Catalina
If you don't have jupyter installed, run `pip install jupyter`.
If you don't have pip installed, run `sudo easy_install pip`.

(Also, it seems less of a handful to get things working on bash rather than zsh)

