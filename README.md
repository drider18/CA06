This assignment is a model built to recommend movies based on criteria given to it. It is given a movie and then will find five movies similar to it that the viewer might like. It uses a relatievly small movie dataset in order to do this. 

The following packages must be imported to run the code: 

import pandas as pd
import numpy as np
from sklearn.neighbors import KNeighborsClassifier
from sklearn.neighbors import NearestNeighbors


Following that, the code can be ran all the way through in order to find the nearest five movies to "The Post." In the future, I would further this project by asking the viewer for a movie title and, in a much more expansive dataset, finding that movie and the five closest movies to it. This would be a much more practical use rather than having the user input various criteria in this model. 
