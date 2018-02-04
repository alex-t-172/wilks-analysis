# wilks-analysis

Wilks scores (https://en.wikipedia.org/wiki/Wilks_Coefficient) are a way of normalizing weights lifted in Powerlifting between bodyweights and genders (as heavier male lifters will in general always be able to lift more weight) - it can be thought of as a measure of how 'good' a powerlifter is.

However, only one journal article has been written on validating the Wilks formula, in 1999, which only looked at ~60 lifters. Experience in use of Wilks has shown it works well as a method for normalizing scores between bodyweights, but the appropriateness of the formula as a way of normalizing between genders is more uncertain, and to my mind it is odd how some of the coefficients (in the link above) in the formula are so different. 

The OpenPowerlifting project (http://www.openpowerlifting.org) contains a large store of data on meet performances of individual powerlifters, and in this project I am exploring this data (with Jupyter notebooks), and trying to ascertain if the Wilks formula as currently prescribed has any gender bias or if it is indeed a fair way of normalizing scores between genders.

    This page uses data from the OpenPowerlifting project, http://www.openpowerlifting.org.
    You may download a copy of the data at https://github.com/sstangl/openpowerlifting.
