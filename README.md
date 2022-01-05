# Hello MNIST in Grid

This uses a dockerfile with Cuda 11.3 and pytorch lightning 1.5.1.

```
git clone https://github.com/filintod/hello_mnists.git
cd hello_mnists
grid run --instance_type g4dn.xlarge --dockerfile Dockerfile pl_cifar10.py
```
