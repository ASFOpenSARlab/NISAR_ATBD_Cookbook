# NISAR Level-3 ATBD Cookbook

<img src="assets/2022_NISAR_Beauty_03.png" alt="thumbnail" width="800"/>

[![nightly-build](https://github.com/ASFOpenSARlab/ASF_Cookbook_Template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ASFOpenSARlab/ASF_Cookbook_Template/actions/workflows/nightly-build.yaml)


This Cookbook compiles the NISAR Level-3 Algorithm Theoretrical Basis Document notebooks into a single location.

The ATBD notebooks are synced with the originals in their upstream repositories each night.


## ATBDs

1. Wetland Inundation
2. Crop Area
3. Biomass
4. Sea Ice Motion
5. Solid Earth
6. Forest Disturbance


## Running the Notebooks

### Running in a Jupyter Hub

If you are working in a Jupyter Hub that allows you to build Pixi environments, such as [OpenSARLab](https://opensarlab-docs.asf.alaska.edu/user-guides/opensarlab/), use the following steps to run the notebooks in this cookbook.

1. Clone the repository:

   ```bash
    git clone https://github.com/ASFOpenSARlab/NISAR_ATBD_Cookbook.git
   ```

1. Run the `notebooks/software_environment.ipynb` notebook.

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "your_account/your_cookbook" with the GitHub org or user name and title of your cookbook repository)

1. Clone this repository:

   ```bash
    git clone https://github.com/your_account/your_cookbook.githttps://github.com/ASFOpenSARlab/NISAR_ATBD_Cookbook.git

1. Move into the `NISAR_ATBD_Cookbook` directory
   ```bash
   cd NISAR_ATBD_Cookbook
   ```
1. Launch in Jupyter Lab with the included Pixi environment
    ```bash
    pix run lab
    ```
