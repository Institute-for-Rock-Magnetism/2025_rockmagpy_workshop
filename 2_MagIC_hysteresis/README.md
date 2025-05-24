# Anatomy of a MagIC contribution and processing data with `rockmagpy`

The Magnetics Information Consortium (MagIC), hosted at http://earthref.org/MagIC is a database that serves as a Findable, Accessible, Interoperable, Reusable (FAIR) archive for paleomagnetic and rock magnetic data. Its data model is fully described here: [https://www2.earthref.org/MagIC/data-models/3.0](https://www2.earthref.org/MagIC/data-models/3.0). Each contribution is associated with a publication via the DOI.  

There are nine data tables. The fields associated with these tables are detailed here: https://www2.earthref.org/MagIC/data-models/3.0. The tables associated with all studies that have measurement level data are:

- contribution: metadata of the associated publication.
- locations: metadata for locations, which are groups of sites (e.g., stratigraphic section, region, etc.)
- sites: metadata and derived data at the site level (units with a common expectation)
- samples: metadata and derived data at the sample level.
- specimens: metadata and derived data at the specimen level.
- measurements: metadata and measurements at the specimen level.

These additional tables can be provided:
- criteria: criteria by which data are deemed acceptable
- ages: ages and metadata for sites/samples/specimens
- images: associated images and plots.  

## Part 1: Let's upload a contribution! 

1. Log-in to MagIC/Earthref (https://www2.earthref.org/MagIC)
2. Go to upload tool (https://www2.earthref.org/MagIC/upload)
3. Download a MagIC contribution containing hysteresis and backfield data from this Github repository ()
4. Go back to main upload page and let's drag and drop the file to upload

   <img src="images/upload_data.png" width="500"/>
5. Upon uploading, we can examine the tables which are parsed and matched up with the table name and data model fields

   <img src="images/import_data.png" width="500"/>
6. Click the upload button in the lower right, which will bring you to an upload page where you can click through to upload data into your private workspace
   
   <img src="images/private_workspace.png" width="500"/>
7. Here we add the lab for the study `Institute for Rock Magnetism` (then click save), and then click to validate the contribution
   
   <img src="images/manage_contribution.png" width="500"/>
   The contribution won't fully validate since MagIC requires a DOI for the study. We could add that, but let's not as these data are already available in MagIC.  
8. Once a study is validated, a contribution can be published. However, prior to full validation or prior to a DOI for a publication a contribution in a private workspace can be shared with a private link. Sharing such a link enables data to be made available data analysis and for peer review. Note that the DOI for the contribution (Future Data DOI) is already available at this stage which enables the data to be properly referenced within a manuscript when it is submitted. 

   <img src="images/private_share.png" width="400"/>

# Part 2: Inspecting the contribution and processing hysteresis data

We will use a Jupyter notebook that is hosted on the EarthRef.org JupyterHub server to process:

 https://jupyterhub.earthref.org/ 

This JupyterHub enables you to run PmagPy code without having to install anything locally. You can get to it via the MagIC website:

<img src="images/jupyter_link.png" width="500"/>

Once you are on JupyterHub, open the `rockmag_set_up.ipynb` notebook:

By executing cells in this setup notebook, you will install the workshop materials into your JupyterHub. We will now be working in a notebook called `rockmag_data_unpack.ipynb` within the `2_MagIC_hysteresis` folder of the `2025_Rockmagpy_workshop` folder.

We will use this notebook to inspect a MagIC contribution using `PmagPy` functions and then analyze/visualize hysteresis data using `rockmagpy` functions.