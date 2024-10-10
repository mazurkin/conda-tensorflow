# tensorflow

## environment

Ubuntu 22.04

```bash
$ apt list --installed | grep cuda | sort
libcudart11.0/jammy,now 11.5.117~11.5.1-1ubuntu1 amd64 [installed,automatic]
nvidia-cuda-dev/jammy,now 11.5.1-1ubuntu1 amd64 [installed,automatic]
nvidia-cuda-gdb/jammy,now 11.5.114~11.5.1-1ubuntu1 amd64 [installed,automatic]
nvidia-cuda-toolkit-doc/jammy,jammy,now 11.5.1-1ubuntu1 all [installed,automatic]
nvidia-cuda-toolkit/jammy,now 11.5.1-1ubuntu1 amd64 [installed]
```

```bash
$ apt list --installed | grep -e '^nvidia' | sort
nvidia-compute-utils-535/jammy-updates,jammy-security,now 535.183.01-0ubuntu0.22.04.1 amd64 [installed,automatic]
nvidia-cuda-dev/jammy,now 11.5.1-1ubuntu1 amd64 [installed,automatic]
nvidia-cuda-gdb/jammy,now 11.5.114~11.5.1-1ubuntu1 amd64 [installed,automatic]
nvidia-cuda-toolkit-doc/jammy,jammy,now 11.5.1-1ubuntu1 all [installed,automatic]
nvidia-cuda-toolkit/jammy,now 11.5.1-1ubuntu1 amd64 [installed]
nvidia-driver-535/jammy-updates,jammy-security,now 535.183.01-0ubuntu0.22.04.1 amd64 [installed]
nvidia-firmware-535-535.183.01/jammy-updates,jammy-security,now 535.183.01-0ubuntu0.22.04.1 amd64 [installed,automatic]
nvidia-kernel-common-535/jammy-updates,jammy-security,now 535.183.01-0ubuntu0.22.04.1 amd64 [installed,automatic]
nvidia-kernel-source-535/jammy-updates,jammy-security,now 535.183.01-0ubuntu0.22.04.1 amd64 [installed,automatic]
nvidia-opencl-dev/jammy,now 11.5.1-1ubuntu1 amd64 [installed,automatic]
nvidia-prime/jammy,jammy,now 0.8.17.1 all [installed,automatic]
nvidia-profiler/jammy,now 11.5.114~11.5.1-1ubuntu1 amd64 [installed,automatic]
nvidia-settings/jammy,now 510.47.03-0ubuntu1 amd64 [installed,automatic]
nvidia-utils-535/jammy-updates,jammy-security,now 535.183.01-0ubuntu0.22.04.1 amd64 [installed,automatic]
nvidia-visual-profiler/jammy,now 11.5.114~11.5.1-1ubuntu1 amd64 [installed,automatic]
nick@mazurkin-p16l:~/work/eden/conda/tensorflow$ apt list --installed | grep -e '^nvidia' | sort^C
```

## installation

```bash
make env-init
make env-create
```
