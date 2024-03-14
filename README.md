# Demo of HashiCorp Vault Key Management Secrets Engine with AWS KMS, Azure Key Vault, and GCP Cloud KMS.
This is using a Jupyter notebook to execute the steps required.
It assumes that you have HashiCorp Vault installed and configured on your side and also access to an AWS account.

The Key Management Secrets Engine feature will require a Vault Enterprise license.

You can use Visual Studio Code to run the notebook by:
- Installing "Jupyter" extension. Ref: https://www.alphr.com/vs-code-open-jupyter-notebook/
- Install the jupyter kernel for bash. Ref: https://pypi.org/project/bash_kernel/
```shell
pip install bash_kernel
python -m bash_kernel.install
```
