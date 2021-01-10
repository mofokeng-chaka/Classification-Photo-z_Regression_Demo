# Classification and Photo-z Regression of Astronomical Sources 

<img width="400" alt="Screenshot 2021-01-10 at 06 58 41" src="https://user-images.githubusercontent.com/42966715/104114837-78225f00-5311-11eb-8fab-02474b954ad5.png"><img width="600" height="500" alt="Screenshot 2021-01-10 at 06 51 02" src="https://user-images.githubusercontent.com/42966715/104114726-6096a680-5310-11eb-8d34-cbb91d5efc30.png">

This tutorial uses two machine learning algorithms: random forest and k-nearest neighbour classifiers to classify three different classes (stars, galaxies and quasars) and also estimate photometric redshifts (for galaxies and quasars) by using colour magnitudes as features to learn. The reference dataset uses the corrected photometric magnitudes from SDSS together with the corresponding WISE magnitudes. 

The tutorial uses a reference dataset : **sdss_all_small_dr16_allwise_red.fits.gz** - https://drive.google.com/file/d/1_c1IyvpbT-v3LRuho3rNQPMCWDD24Hde/view?usp=sharing

### Dependencies

* [pandas](https://pandas.pydata.org/)
* [sklearn](scikit-learn.org/)
* [astropy](https://www.astropy.org)
* [numpy](https://numpy.org)
* [matplotlib](https://matplotlib.org)
* [timeit](https://docs.python.org/3/library/timeit.html)
* [itertools](https://docs.python.org/3/library/itertools.html)

#### Step 1. Download the dataset

Use the link provided above to download the referece dataset **sdss_all_small_dr16_allwise_red.fits.gz** and place it in the same directory as the jupyter notebook.

#### Step 2. Run demo

Run all the cells in the notebook to make sure all the dependencies are installed correctly.

#### Step 3. Improving results

Last step, after completion step 2 is the optimization step. To optimize, tweak the parameters of the models (defined under *_classifier* and *_regressor* functions) to produce optimal results 
