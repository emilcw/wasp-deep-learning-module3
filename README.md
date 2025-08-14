# How to run Diffusion part

1. Install [conda](https://anaconda.org/anaconda/conda) on your machine.
2. Build the conda environment from .yml file.

```
# install
conda env create -f fashion_mnist_env.yml

# activate
conda activate fashion_mnist_env
```
3. Open main.ipynb in your editor of choice (like vscode)
4. If needed, select the conda environment in the editor as well (should ask for it in vscode)
5. Run all segments in sequence, this will automatically download the dataset, build the model and start the training.
