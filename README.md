# SUB-GENRE CLASSIFICATION
### A Capstone by Brandon Rose for Lighthouse Labs
#### Dec 8, 2022

## Tech Stack
**Platforms**: Python, Jupyter

**Libraries**: [Pandas](https://pandas.pydata.org/docs/), [NumPy](https://numpy.org/doc/stable/), [Spotipy](https://spotipy.readthedocs.io/en/2.21.0/), [Librosa](https://librosa.org/doc/latest/index.html), [Requests](https://requests.readthedocs.io/en/latest/)

**Modelling**: [SciKit-Learn](https://scikit-learn.org/stable/modules/classes.html), [Keras](https://keras.io/api/)

## Introduction

With the advent of content streaming, music enjoyment has transformed for the consumer. Wireless networks and smartphones have created the environment for music to be accessible at the touch of a screen, and no other app has done quite as well as Spotify. This platform has allowed music listeners and artists to connect without the need for a publishing agency or record store, and while this has been powerful in the paradigm shift from disk to digital, there are new issues growing with the platforms ability to accurately classify individual tracks. With the platform relying on artists to classify their own music on the artist endpoint, we are losing the ability to properly identify the nuanced sounds within a specific track, and instead are broad brushing every song with the biased labels the artist chooses for their brand—should they even remember to input anything.

The issue drives deeper with the introduction of Spotify's API, which allows third parties and developers to control spotify using programming languages like Python through libraries like Requests. Spotify's own curated playlists have had [issues in the past](https://www.reddit.com/r/spotify/comments/41lkoe/who_else_thinks_spotifys_curated_playlists_are/), and there seems to be some moderate improvement on how Spotify can identify core sounds in their playlist generation algorithm. One major issue, however, is the apps inability to pick up subtle nuances and inferences between sub-genres. Spotify still seems to have issues with curating accurate playlists, to a point where content creators are garnering thousands of views [pointing out the inconsistencies in these playlists](https://www.youtube.com/watch?v=w5US_28-jrE). 