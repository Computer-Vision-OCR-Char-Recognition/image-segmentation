# Image segmentation

Colour spaces:

- RGB
- HSV
- HLS
- YCrCb
- Lab (CIE L*a*b*)
- Luv (CIE L*u*v*)


Clustering techniques:

- Mean-shift
- K-means (2, 3, 4, 5 colours)
- Affinity propagation


http://scikit-learn.org/stable/auto_examples/cluster/plot_affinity_propagation.html#example-cluster-plot-affinity-propagation-py


heroku plugins:install heroku-redis
heroku redis:maxmemory --policy allkeys-lru
> allkeys-lru evict keys trying to remove the less recently used keys first.