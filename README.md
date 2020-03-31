# scikit-learn-contribution
# ----------------------------

## Presentation + .whl & .tar.gz files + Test Cases folder

### New function called train_test_val_spilt() implemented based on the existing function train_test_split(). Only if a value for val_size is specified (i.e. is not None or 0.0) then each input array will be split in to three subsets and returned.




### --------------------------------------------------------------------

## TO CREATE NEW ENV using the TEST PYPI

compiling from source : https://test.pypi.org/project/scikit-learn-3way-split/

The dependencies are not picked up automatically for some reason and need to be installed manually.

### --------------------------------------------------------------------
Create the environment and activate it

pip install numpy>=1.14.0

pip install scipy>=1.1.0

pip install joblib>=0.11

pip install threadpoolctl>=2.0.0

pip install -i https://test.pypi.org/simple/ scikit-learn-3way-split

Note: pandas is only required for this particular test script

pip install pandas

pip install jupyter notebook

### --------------------------------------------------------------------
### ********************************************************************
### --------------------------------------------------------------------

## TO CREATE NEW ENV using the PYPI 

compiling from source : https://pypi.org/project/scikit-learn-3way-split/

Here the dependencies are picked up automatically.

### --------------------------------------------------------------------
Create the environment and activate it

pip install scikit-learn-3way-split

Note: pandas is only required for this particular test script

pip install pandas

pip install jupyter notebook

### --------------------------------------------------------------------
