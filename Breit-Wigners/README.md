These datasets are variations on a standard Breit-Wigner lineshape. 
The *amplitude* is given by

$$\psi = \frac{1}{(M-M_0) + \frac{i\Gamma}{2}}$$


# Single Breit-Wigner

https://github.com/mattbellis/datasets_for_testing_fitting_frameworks/blob/main/Breit-Wigners/single_BW_000.txt

[Raw dataset](https://raw.githubusercontent.com/mattbellis/datasets_for_testing_fitting_frameworks/main/Breit-Wigners/single_BW_000.txt)

Dataset description
* Text file
* 100,000 data points
* Single column
* Header (1)
* Values
  * Masses (GeV/c^2)
 
## Suggested fits
### Fit to a Gaussian

* Parameters and required labels for downstream comparisons
  * `mean`: Mean of the Gaussian function
  * `sigma`: Sigma (width) of the Gaussian Function
 
### Fit to a Breit-Wigner

* Parameters and required labels for downstream comparisons
  * `m0`: Pole of the Breit-Wigner function
  * `gamma`: Residue (width) of the Breit-Wigner Function
 
### Fit to a Breit-Wigner with finite resolution

* Parameters and required labels for downstream comparisons
  * `m0`: Pole of the Breit-Wigner function
  * `gamma`: Residue (width) of the Breit-Wigner Function
  * `sigma`: Mass resolution (Gaussian) in GeV/c^2

 
# Two interferig Breit-Wigners

https://github.com/mattbellis/datasets_for_testing_fitting_frameworks/blob/main/Breit-Wigners/double_BW_000.txt

[Raw dataset](https://raw.githubusercontent.com/mattbellis/datasets_for_testing_fitting_frameworks/main/Breit-Wigners/double_BW_000.txt)

Dataset description
* Text file
* 100,000 data points
* Single column
* Header (1)
* Values
  * Masses (GeV/c^2)
 
## Suggested fits
### Fit to a Gaussian

* Parameters and required labels for downstream comparisons
  * `mean`: Mean of the Gaussian function
  * `sigma`: Sigma (width) of the Gaussian Function
 
### Fit to two interfering Breit-Wigners

* Parameters and required labels for downstream comparisons
  * `m0_1`: Pole of the lower-mass Breit-Wigner function
  * `gamma_1`: Residue (width) of the lower-mass Breit-Wigner Function
  * `m0_2`: Pole of the higher-mass Breit-Wigner function
  * `gamma_2`: Residue (width) of the higher-mass Breit-Wigner Function
 
### Fit to a Breit-Wigner with finite resolution

* Parameters and required labels for downstream comparisons
  * `m0_1`: Pole of the lower-mass Breit-Wigner function
  * `gamma_1`: Residue (width) of the lower-mass Breit-Wigner Function
  * `m0_2`: Pole of the higher-mass Breit-Wigner function
  * `gamma_2`: Residue (width) of the higher-mass Breit-Wigner Function
  * `sigma`: Mass resolution (Gaussian) in GeV/c^2


# Two interferig Breit-Wigners + finite mass resolution

https://github.com/mattbellis/datasets_for_testing_fitting_frameworks/blob/main/Breit-Wigners/double_BW_smeared_000.txt

[Raw dataset](https://raw.githubusercontent.com/mattbellis/datasets_for_testing_fitting_frameworks/main/Breit-Wigners/double_BW_smeared_000.txt)

Dataset description
* Text file
* 100,000 data points
* Single column
* Header (1)
* Values
  * Masses (GeV/c^2)
 
## Suggested fits
### Fit to a Gaussian

* Parameters and required labels for downstream comparisons
  * `mean`: Mean of the Gaussian function
  * `sigma`: Sigma (width) of the Gaussian Function
 
### Fit to two interfering Breit-Wigners

* Parameters and required labels for downstream comparisons
  * `m0_1`: Pole of the lower-mass Breit-Wigner function
  * `gamma_1`: Residue (width) of the lower-mass Breit-Wigner Function
  * `m0_2`: Pole of the higher-mass Breit-Wigner function
  * `gamma_2`: Residue (width) of the higher-mass Breit-Wigner Function
 
### Fit to a Breit-Wigner with finite resolution

* Parameters and required labels for downstream comparisons
  * `m0_1`: Pole of the lower-mass Breit-Wigner function
  * `gamma_1`: Residue (width) of the lower-mass Breit-Wigner Function
  * `m0_2`: Pole of the higher-mass Breit-Wigner function
  * `gamma_2`: Residue (width) of the higher-mass Breit-Wigner Function
  * `sigma`: Mass resolution (Gaussian) in GeV/c^2


