# jupyter-kernel-installer

Un/installs a virtual environment into Jupyter Lab.

## Usage

In your virtual environment, run:

```sh
jupyter-kernel-installer ${KERNEL_NAME} ${COMMAND}
```

where `KERNEL_NAME` is the name of the kernel you want to un/install and `COMMAND` is "install" or "uninstall".

Using `curl`:

```sh
curl -sSL https://raw.githubusercontent.com/janjagusch/jupyter-kernel-installer/0.1.0/jupyter-kernel-installer | bash -s ${KERNEL_NAME} ${COMMAND}
```