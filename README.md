# AI Reference Architectures
This repository contains the recommended ways to train and deploy models on Azure. It ranges from running massively parallel hyperparameter tuning using Hyperdrive to deploying deep learning models on Kubernetes. Each path is arranged as a tutorial which takes you step by step through the process to train or deploy your model. The tutorials are arranged as Jupyter notebooks so you can simply download them and start running them. 

# Requirements
The tutorials have been mainly tested on Linux VMs in Azure. They haven't been tested on Windows yet. Each path may have slightly different requirements such as GPU for some of the deep learning ones. For more details please consult the readme in each path.

# Getting Started
This repo is arranged as submodules and therefore you can either pull all the tutorials or simply the ones you want. To pull all the tutorials simply run:

```bash
git clone --recurse-submodules -j8 https://github.com/Microsoft/AIReferenceArchitectures.git
```

if you have git older than 2.13 run:

```bash
git clone --recursive https://github.com/Microsoft/AIReferenceArchitectures.git
```


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
