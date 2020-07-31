# Classification and Photo-z Regression of Astronomical Sources 

<img alt="Screenshot 2020-07-30 at 19 36 29" src="https://user-images.githubusercontent.com/42966715/88962852-4eb3d080-d2a7-11ea-9b65-9ce540415c1a.png" width="455"/><img alt="photo-z" src="https://user-images.githubusercontent.com/42966715/88967085-99384b80-d2ad-11ea-867b-41dd81bc38c3.png" width="375"/> 

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

Last step, after completion step 2 the optimization step. Tweak the parameters of the models (defined under *_classifier* and *_regressor* functions) to produce optimal results 
