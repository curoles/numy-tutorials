# Numy tutorials

Tutorials are in the format of Jupyter notebook. To install Jupyter use following command:

```terminal
pip3 install jupyterlab
```

Install packages required by IElixir:

```terminal
sudo apt-get install libzmq3-dev libsqlite3-dev
```

Install IElixir:

```terminal
$ git clone https://github.com/pprzetacznik/IElixir.git
$ cd IElixir/
$ mix deps.get
$ MIX_ENV=prod mix compile
$ ./install_script.sh
```

Start Jupyter server with command `jupyter lab` and open URL 
`http://localhost:8888/lab` in your web browser.

<!--http://aipotato.com/2019/04/making-graphs-using-elixir-inside-jupyter-notebook/-->



