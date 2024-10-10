# tensorflow

## environment

Ubuntu 22.04, not cuda toolkit installed, just nvidia 550 drivers

```bash
$ apt list --installed | grep cuda | sort
(null)
```

```bash
$ apt list --installed | grep -e '^nvidia' | sort
nvidia-compute-utils-550/jammy-updates,jammy-security,now 550.107.02-0ubuntu0.22.04.1 amd64 [installed,automatic]
nvidia-driver-550/jammy-updates,jammy-security,now 550.107.02-0ubuntu0.22.04.1 amd64 [installed]
nvidia-firmware-550-550.107.02/jammy-updates,jammy-security,now 550.107.02-0ubuntu0.22.04.1 amd64 [installed,automatic]
nvidia-kernel-common-550/jammy-updates,jammy-security,now 550.107.02-0ubuntu0.22.04.1 amd64 [installed,automatic]
nvidia-kernel-source-550/jammy-updates,jammy-security,now 550.107.02-0ubuntu0.22.04.1 amd64 [installed,automatic]
nvidia-prime/jammy,jammy,now 0.8.17.1 all [installed,automatic]
nvidia-settings/jammy,now 510.47.03-0ubuntu1 amd64 [installed,automatic]
nvidia-utils-550/jammy-updates,jammy-security,now 550.107.02-0ubuntu0.22.04.1 amd64 [installed,automatic]
```

## installation

```bash
make env-init
make env-create
```
