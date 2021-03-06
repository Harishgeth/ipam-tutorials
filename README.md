# IPAM Graduate Summer School

On Deep Learning, Feature Learning
July 9 - 27, 2012

[More info here.](http://www.ipam.ucla.edu/programs/gss2012/) 


## Day 1: Setup

* Welcome to the Practical Sessions for the summer school

  * Objectives:

    * implementation-level understanding of supervised and unsupervised learning algorithms

      * Many algorithms are more similar than researchers in the field
        might have you believe!

    * a sense of hyper-parameter sensitivities and run-times for various
      algorithms

    * appreciation for two approaches to programming deep learning experiments

      * Code fragments for interactive exploration

      * Full-blown application

    * exposure to programming languages and software stacks:

      * Python, NumPy, SciPy, Theano

      * Lua, Torch7


  * Schedule: 1 hour on four days this first week

    * Monday 12PM - 1PM: _Lua/Torch, Python/Theano, logging in to EC2_

    * Tuesday 4PM - 5PM: _Supervised Learning in Lua and Python_

    * Wednesday 4PM - 5PM: _Unsupervised Learning in Lua and Python_

    * Thursday 4PM - 5PM: _TBA_


* Session Structure

  * Time is short for these practical sessions!

  * Each day will start with two walk-throughs of things you can experiment with
    (we'll try to be quick, to give you time afterward!)

  * After the walk-throughs you can log in to an Amazon EC2 node where we've set
    things up.

  * For lack of time - you will have to choose whether to do the Lua thing or
    the Python thing in the in-classroom time each day.

      * We will negotiate with the organizers to leave the EC2 node up after the sessions

      * We will be around all week - feel free to ask questions any time!

      * We will be available by email after the first week.

* 10 mins crash course in Python, numpy

  * intro to IPython notebook

* 10 mins crash course in Lua, Torch7

  * will review very basic Lua and Torch concepts, to get people started

* Remaining time - getting people into groups and setting them up to run the sample code
  on laptop or EC2. Once they get it running, they can go for lunch or stick
  around and play with things.


## Day 2: Supervised Learning

* Models: SVM, MLP, ConvNets, (Logistic Regression?)

* Data Sets: MNIST, CIFAR, Google Street View House Numbers (SVHN).
  SVHN is an interesting new data set, very few results are available at this time 
  (and is more computer visionny that MNIST).

* Optimization Methods: SGD, ASGD, L-BFGS; batch vs. mini-batch vs. online


## Day 3: Feature Learning

* Python: Imprinting, K-Means, Autoencoder, De-noising Autoencoder, RBM,
  (Sparse Coding?)

* Torch: Linar Autencoder, Convolutional Autoencoder, Linear and 
  Convolutional PSD (Predictive Sparse Decomposition) Autoencoder


## Day 4: To Be Decided

* Persitant Contrastive Divergence?

* Theano?

* Recurrent Neural Networks?

* GPU Programming 101?

* Torch/nn extensions: write your own modules