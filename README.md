# Bayesian Optimization


Introductionary tutorial to run your own Bayesian Optimization campaign.

If you are part of ChemAI or PSL university, feel free to reach out if you need any support or if you

- want to adopt our solutions within your own projects
- need help with the setup
- are interested in Bayesian Optimization in general
- are interested in a code-free UI solution for your lab
- got another reason


# HSF-ChemBO-tutorial

This tutorial is a quick adoption of our proposed dimension-aware hyperprior for hidden-space representations in chemical Bayesian optimization.
The environment is based on [BayBE 0.12.2](https://emdgroup.github.io/baybe/0.12.2/) with Python 3.11.

The underlying publication **Leveraging Hidden-Space Representations Effectively in Bayesian Optimization for Experiment Design through Dimension-Aware Hyperpriors**, can be found [here](https://doi.org/10.1021/acs.jctc.6c00251). A follow up on transfer learning is available [here](https://doi.org/10.1039/d6dd00527f).

Our dimension-aware hyperprior is implemented as a default in newer versions of BayBE.


### Quickstart:

install git

```
https://git-scm.com/install/mac
```

download this repo: 

```
git clone https://github.com/chimie-paristech-CTM/HSF-ChemBO-tutorial
```

install [uv package manager](https://docs.astral.sh/uv/getting-started/installation/)
```
curl -LsSf https://astral.sh/uv/install.sh | sh
```

then run (all packages will be downloaded and saved locally)
```
uv run jupyter-lab
```
...or use vs code. Then execute
```
code .
```
and select the uv environment.
