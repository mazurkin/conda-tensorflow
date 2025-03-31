# tensorflow

## installation

```bash
# create the new conda environment
make env-init

# install the dependencies
make env-create
```

```shell
# setup the password for the notebook server
make notebook-password
```

```bash
# run notebook server
make notebook
```

```bash
# shell with-in the conda environment
make env-shell
```

## environment variables

- `${NB_HOST}` - the listening interface (default is `0.0.0.0`)
- `${NB_PORT_JUPYTER}` - the notebook port (default 18888)
- `${NB_PORT_TBOARD}` - the tensorboard port (default 16006)

## external URL

Resolve the HTTPS url and open the link in the browser:
```shell
echo "http://$(hostname):18888/tree"
```

## tensorflow

- https://www.tensorflow.org/install/source#gpu

## todo

- https://github.com/tensorflow/tensorflow/issues/62075
