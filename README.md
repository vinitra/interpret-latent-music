# Musical Embeddings

**Project for Computers and Music at EPFL, Spring 2022.**

**Team:** 
- Vinitra Swamy
- Viktor Sanca
- Bhargav Srinivasa Desikan
- Manoel Horta Ribeiro

In this project we create and explore latent representations of midi files. We were largely inspired by the paper:

> Pasquale Lisena, Albert Meroño-Peñuela, Raphaël Troncy. MIDI2vec: Learning MIDI Embeddings for Reliable Prediction of Symbolic Music Metadata, to appear in Semantic Web Journal, Special Issue on Deep Learning for Knowledge Graphs, 2021. http://www.semantic-web-journal.net/content/midi2vec-learning-midi-embeddings-reliable-prediction-symbolic-music-metadata-0, Code: https://github.com/midi-ld/midi2vec

The project is divided across three different notebooks:

1. `01_midi2vec.ipynb` — where we re-implement the MIDI2Vec algorithm
2. `02_data_processing` — where we develop a pipeline to get metadata related to the Lakh MIDI Dataset.
3. `03_explorations` — where we use the embeddings provided in Lisena et al. and perform analyses on the structure of latent representations.

