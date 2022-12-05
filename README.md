# NOTEBOOK OVERVIEW
- quick reference notebooks
  - future_directions.ipynb                 = project summary + ideas for future directions
  - example_queries.ipynb                   = ProductSearch().query()  usage tutorial

- class definitions
  - class_Dataset.ipynb                     = class to handle data
  - class_TokenSearch.ipynb                 = class to grep search tokens
  - class_NeighbourSearch.ipynb             = class to perform nearest-neighbour searching
  - class_ImageSearch.ipynb                 = class to perform image distance metrics
  - class_ProductSearch.ipynb               = class to string everything together to do queries

- generic Jupyter notebook prepping
  - ipynb_setup.ipynb                       = admin notebook for bookkeeping

- exploratory dabbling notebooks
  - exploration.ipynb                       = initial exploratory analysis
  - text_search.ipynb                       = building + testing of TokenSearch() functions
  - img_features.ipynb                      = building + testing of ImageSearch() functions
  - ml_aggcluster.ipynb                     = considering usage of agglomerative clustering
  - ml_kmeans.ipynb                         = considering usage of k-means
  - ml_NearestNeighbors.ipynb               = considering usage of k-nearest neighbours
  - ml_pca.ipynb                            = considering usage of PCA

# FUTURE DIRECTIONS
- `lemmatization` within `TokenSearch` class
  - extract root meanings from search tokens
  - don't want a specific search term to throw off `TokenSearch` class, e.g. strips / stripped / stripy VS strip

- `convolutional neural nets` to replace the `ImageSearch` class
  - I read a lot of good things re CNN's in image search but had no time to play