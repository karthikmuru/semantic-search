# Semantic Search
Semantic search on a million news headlines using approximate nearest neighbor search on sentence embeddings. <br>
Built a data pipline using Apache Beam to preprocess, convert to embeddings and store it as a tfrecord file. Then built an index of these embeddings using Spotify's ANNOY library to perform search.

Dataset: https://www.kaggle.com/therohk/million-headlines

