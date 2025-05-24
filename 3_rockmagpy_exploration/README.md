# rockmagpy in action on MagIC data

In the rockmagpy in action portion of the workshop, we will work through two example rockmagpy notebooks.

## 🧲 [MPMS Verwey Transition Estimation Notebook](https://pmagpy.github.io/RockmagPy-notebooks/MPMS_notebooks/MPMS_verwey_fit.html)

We will run through [this notebook](https://pmagpy.github.io/RockmagPy-notebooks/MPMS_notebooks/MPMS_verwey_fit.html) on JupyterHub that demonstrates a procedure to estimate the temperature of the Verwey transition from remanence upon warming curves developed through MPMS experiments.

---

### 🔧 Notebook Workflow

1. **Import Scientific Python Libraries**: Load necessary Python packages for data analysis and visualization.

2. **Import Data**: Unpack and load MagIC-formatted data into the notebook for analysis.

3. **Estimate the Verwey Transition Temperature**: Utilize remanence upon warming curves to estimate the Verwey transition temperature.

4. **Interactively Fit the Verwey Transition**: Employ interactive widgets to fit the Verwey transition and visualize the results.

5. **Use the `rmag.verwey_estimate` Function**: Apply the `rmag.verwey_estimate` function to calculate the Verwey transition temperature programmatically.

6. **Plot the Second Derivative Curve**: Generate plots of the second derivative of the remanence data to illustrate how the Verwey transition temperature is estimated.

7. **Determine and Record the Verwey Temperatures for Multiple Specimens**: Iterate over multiple specimens to estimate and record their respective Verwey transition temperatures.

8. **Add These Verwey Estimates to the Specimens MagIC Table**: Integrate the estimated Verwey transition temperatures into the MagIC specimens table for comprehensive data management.

## 🧲 [Coercivity Spectra Analysis Notebook](https://pmagpy.github.io/RockmagPy-notebooks/hysteresis_backfield_notebooks/coercivity_unmixing_MaxUnmix.html)

We will also run through [this notebook](https://pmagpy.github.io/RockmagPy-notebooks/hysteresis_backfield_notebooks/coercivity_unmixing_MaxUnmix.html) on JupyterHub that implements the MaxUnMix algorithm for unmixing magnetic coercivity spectra using Python, adapted from the original R-based implementation by Maxbauer et al. (2016).

### 🔧 Notebook Workflow

1. **Import Scientific Python Libraries**: Load necessary Python packages for data analysis and visualization.

2. **Load Example Data**: Import example backfield demagnetization data provided with the MaxUnMix application.

3. **Process Backfield Data**: Smooth and differentiate the backfield data to obtain the coercivity spectrum.

4. **Interactive Fitting**: Utilize interactive widgets to fit the coercivity spectrum with one or more components.

5. **Error Estimation**: Perform bootstrap resampling to estimate uncertainties in the fitted parameters.

6. **Batch Processing**: Apply the unmixing procedure to multiple datasets in a batch mode.