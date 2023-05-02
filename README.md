# Jupyter Notebooks

A collection of some of my own dabblings and ones I've found on the interwebs.
Uses Docker for easy portability and not worrying about python installs.

## Notebooks of ...note ...books

- [tempo.ipynb](tempo.ipnyb) My research with Librosa near real time tempo detection


## Use

Run `docker-compose up` to start two containers, one is a ready-to-go Jupyter Web UI at
[`localhost:8888`](http://localhost:8888).

Or point an IDE (like
[VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks#_connect-to-a-remote-jupyter-server), tested)
to Jupyter server and python kernel at `http://localhost:8889?token=a`.

# ToDo

- Automatically have ready to go static output HTML versions browsable
    - The rendered plots and *-ograms etc images are great to have, could I hack `git lfs`
      for sound renderings too that work with an HTML saved notebook 🤔

