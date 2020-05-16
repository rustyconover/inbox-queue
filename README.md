# Rusty's Mental Inbox

A queue of things that are pending further time to read and understand.

## Pending:

- [ ] [The Matrix Calculus You Need For Deep Learning](https://explained.ai/matrix-calculus/index.html)

- [ ] [My Favorite Talks From Strange Loop 2019](http://stratus3d.com/blog/2019/09/24/my-favorite-talks-from-strange-loop-2019/
)

- [ ] [Transformers from Scratch](http://www.peterbloem.nl/blog/transformers)

- [ ] [Learning to Predict Without Looking Ahead:
World Models Without Forward Prediction](https://learningtopredict.github.io) - I think world models are fascinating.
 
## Recently read (still pending exercises):

<img src="https://images-na.ssl-images-amazon.com/images/I/416KapTtFjL._SX379_BO1,204,203,200_.jpg" width="100px" style="float:left"/> [Generative Deep Learning](https://www.amazon.com/Generative-Deep-Learning-Teaching-Machines/dp/1492041947)

<img src="https://images-na.ssl-images-amazon.com/images/I/51bnimDBPkL._SX379_BO1,204,203,200_.jpg" width="100px"> [Hands-On Unsupervised Learning Using Python: How to Build Applied Machine Learning Solutions from Unlabeled Data](https://www.amazon.com/Hands-Unsupervised-Learning-Using-Python/dp/1492035645)

## In progress:

<img src="https://images-na.ssl-images-amazon.com/images/I/51rGoPuGcSL._SX379_BO1,204,203,200_.jpg" width="100px"> [Practical Time Series Analysis: Prediction with Statistics and Machine Learning](https://www.amazon.com/Practical-Time-Analysis-Prediction-Statistics/dp/1492041653/ref=sr_1_1?crid=349AS4FB79YKS&keywords=time+series+oreilly&qid=1572714244&sprefix=time+series+or%2Cstripbooks%2C165&sr=8-1)


### Percolating ideas:

- Line Wrapping and Contrast Detection 
  - https://github.com/xdamman/js-line-wrap-detector
  - https://developer.mozilla.org/en-US/docs/Web/API/Element/getClientRects
  - https://jsfiddle.net/abrady0/ggr5mu7o/ - The use of ranges to determine which word was clicked, may be useful to determine which words are contained in a bounding box.
- [https://github.com/huseinzol05/NLP-Models-Tensorflow](https://github.com/huseinzol05/NLP-Models-Tensorflow)

- [Gen](https://probcomp.github.io/Gen/tutorials.html)

### Reviewed Papers and links.

  - [MM2RTB: Bringing Multimedia Metrics to Real-Time Bidding](https://arxiv.org/pdf/1708.00255.pdf)
    - Interesting use of both [Memnet](http://memorability.csail.mit.edu/) and [Minimum Barrier Salient Object Detection at 80 FPS](https://cs-people.bu.edu/jmzhang/fastmbd/MBS_preprint.pdf).
    - Implementation of MBS 80 [pyimgsaliency](https://github.com/yhenon/pyimgsaliency/blob/master/README.md)
    
  - [Using the DOM Tree for Content Extraction](https://arxiv.org/pdf/1210.6113.pdf)
  
  - [Enhancing Email Functionality using Late Bound Content](https://arxiv.org/pdf/1907.01423.pdf)
    - basically render emails as gifs/images rather than including them in emails so there can be "live" content.
  - [Learning Visual Importance for Graphic Designs and Data Visualizations](https://vcg.seas.harvard.edu/publications/learning-visual-importance-for-graphic-designs-and-data-visualizations/paper)
    - https://github.com/cvzoya/visimportance
  
#### Image Saliency

  - [https://github.com/remega/Sal-DCNN](https://github.com/remega/Sal-DCNN)
  - [SID4VAM](https://arxiv.org/pdf/1910.13066.pdf)
  - [Contextual Encoder-Decoder Network for Visual Saliency Prediction](https://github.com/alexanderkroner/saliency)
  
#### Image Memorability

  - [AMNet: Memorability Estimation with Attention](https://github.com/ok1zjf/AMNet)
  - [https://github.com/stevemar/powerai-image-memorability](https://github.com/stevemar/powerai-image-memorability)
  - [GANalyze: Toward Visual Definitions of Cognitive Image Properties](https://arxiv.org/pdf/1906.10112.pdf)
     - This paper applies GANs to adjust an image in such a way to increase or decrease memorability, aesthetics or emotional valience. Unfortunetely, the GANs are only trained on ImageNet classes so it is not yet possible to apply them to the full spectrum of imagery found in the real world.  By applying the GAN to generated imagery and looking at the changes made by the GAN when attempting to increase a property of an image there is a way to start to understand what changes would increase or decrease the desired property.
     
#### Email Actions

  - [GMail Email Actions](https://developers.google.com/gmail/markup/actions/actions-overview)
 
#### Emotion Detection
  
  - [Joint Image Emotion Classification and Distribution Learning via Deep Convolutional Neural Network](https://github.com/sherleens/EmotionDistributionLearning)

#### Cool Notebooks

  - https://observablehq.com/@mourner/simple-rectangle-packing?collection=@mourner/algorithms
  - https://vega.github.io/vega-lite/examples/

#### Perfect Hash Functions

  - https://10xgenomics.github.io/rust-boomphf/master/boomphf/index.html
  - https://towardsdatascience.com/turn-amazon-s3-into-a-spatio-temporal-database-40f1a210e943

  - https://github.com/awslabs/s3-managed-download-js
  - https://www.indiehackers.com/article/we-wasted-50k-on-google-ads-so-you-dont-have-to-355a425b27

#### RTree in SQLite

  - http://sqlite.1065341.n5.nabble.com/R-Tree-module-and-double-precision-td61806.html 
  
#### Hilbert Curves
  - https://www.reddit.com/r/rust/comments/dx2k2q/hilbert_curve_transformation_crate_for/
  - https://github.com/davidmoten/hilbert-curve - interesting implementation of range querying using Hilbert curves.

#### Weather Grids
  - https://www.weather.gov/mdl/digitalforecastservices_home
  - https://www.nws.noaa.gov/mdl/synop/gmos/gmosgrib2_wxinfo.html
  - https://leafletjs.com/examples/choropleth/
  - https://www.weather.gov/mdl/nbm_home
  - https://www.weather.gov/mdl/grib_design
  - https://nomads.ncep.noaa.gov/
  - http://home.chpc.utah.edu/~u0553130/Brian_Blaylock/cgi-bin/hrrr_download.cgi?model=hrrr&field=sfc&date=2020-02-11&link2=metadata
  - https://rapidrefresh.noaa.gov/GRIB2Table_GSDrap_2d.txt
  
#### Air Travel Delays
  - https://transtats.bts.gov/DL_SelectFields.asp

#### Leaflet stuff
  - https://github.com/socib/Leaflet.TimeDimension
  
#### Hexagon based convolutions
  - https://github.com/ai4iacts/hexagdly
  - H3 Encoder for Tensorflow v1: https://github.com/uber/ludwig/blob/a594ab5fd93337cbae3bdc4b8719509c1739e129/ludwig/models/modules/h3_encoders.py
  
#### Healpix - interesting pixelization on the sphere

  - https://healpix.sourceforge.io/html/csub.htm
  - https://healpix.sourceforge.io/html/intro_Geometric_Algebraic_Propert.htm

### Hilbert Curve Querying
  
  - https://github.com/davidmoten/hilbert-curve/blob/master/src/main/java/org/davidmoten/hilbert/SmallHilbertCurve.java#L188
  - https://github.com/davidmoten/sparse-hilbert-index/tree/master/src/main/java/com/github/davidmoten/shi
  - https://stackoverflow.com/questions/53472433/range-search-with-hilbert-curve-index
  
### Train Delays

  - https://link.springer.com/article/10.1007/s40534-019-0188-z
  
### KL Divergence
  - https://medium.com/@cotra.marko/making-sense-of-the-kullback-leibler-kl-divergence-b0d57ee10e0a
  
### Probability Distributions
  - https://medium.com/hal24k-techblog/a-guide-to-generating-probability-distributions-with-neural-networks-ffc4efacd6a4
