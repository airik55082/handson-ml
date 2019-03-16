- conda
  - environments
    [conda environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
    - `conda create --name myenv`
    - `conda install -n myenv scipy`
    - `conda activate myenv`
    - `conda deactivate`
    ```
    conda create --name handson-ml
    conda activate handson-ml
    ```
- `tar xzf housing.tgz`
- [pandas.DataFrame.where](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.where.html)
  - `Replace values where the condition is False.`
- [Jupyter Notebook Keyboard Shortcuts - Mac](https://gist.github.com/kidpixo/f4318f8c8143adee5b40)
- [Conda package management](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-pkgs.html)
  - Install new package; will be prompted with `y`/`n` if new is available
    - `conda update conda`
- Installing `scikit-learn`; Conda didn't recognize it previously
  - `conda install scikit-learn`