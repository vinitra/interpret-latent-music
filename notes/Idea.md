**Idea**: Identify musical features in deep learning representations of sound (genre, sur\prise, tempo, tonality, etc)

**Concrete procedure:** Train an encoder (midi2Vec, musicVAE) on a corpus across genres (from raw MIDI)

**Question:** How well do transformer models match up to human intuitions about musical features?

1. **similarities between genres of music that we expect** 
    - i.e. jazz is closer to classical piano than to rock
    - do metrics in the distances in embeddings
    - diversities within genres
    - diversity within decades(?)
2. **ways to compare between MFCCs (what kind of information is being encoded in MFCCs vs neural networks)**
3. **Interpretability analysis of the latent space (of music vectors) to find dimensions of pitch, tempo, tonality, timbre, “the drops” in electronic music, etc.**
    - each song is a vector represented in the vector space
    - analogous to word-embedding literature, we could identify transformations in this vector space for restructure the space into these dimensions
    - PCA latent space exploration, T-SNE, intuition comparison
4. **“playful notebook” to explore music relationships in embedded space**


**Datasets:**

176,000 midi files, 46,000 aligned, genres are varied

MIDI files, data granularity —

- lengths, instruments, instrument maps, tempo changes, time of event in midi files, time signature changes

**Links:**

[MultitrackVAE](https://colab.research.google.com/github/magenta/magenta-demos/blob/master/colab-notebooks/Multitrack_MusicVAE.ipynb)
[UChicago Deep Learning Tutorial](https://github.com/UChicago-Thinking-Deep-Learning-Course/Tutorials-Homework-Notebooks/tree/main/week-6)
[Magenta](https://magenta.tensorflow.org/)
[Midi2Vec repo](https://github.com/midi-ld/midi2vec)
[Midi2Vec embeddings](https://github.com/pasqLisena/midi-embs)
[Midi2Vec paper](http://www.semantic-web-journal.net/system/files/swj2844.pdf)
