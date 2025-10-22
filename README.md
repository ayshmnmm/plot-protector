# Plot Protector
Spoiler detection in movie/tv show reviews using machine learning

## Quickstart
0. Prerequisites:
   - Install Anaconda or Miniconda
   - Install Git and Git LFS
   - Run `git lfs install` to set up Git LFS.

1. Clone the repository:
   ```bash
   git clone git@github.com:ayshmnmm/plot-protector.git
   ```
2. Change to the project directory:
   ```bash
   cd plot-protector
   ```
3. Create a conda environment:
   ```bash
   conda env create -f environment.yml
   ```
4. Activate the conda environment:
   ```bash
   conda activate pp
    ```

## Project Structure
- `data/`: Contains processed datasets. (gitignored due to size)
- `notebooks/`: Jupyter notebooks for data exploration, data preprocessing and model development.
- `src/`: Source code for data processing, model training, prediction and evaluation.
- `models/`: Saved machine learning models. (gitignored)
- `deployment/`: Web extension source code.


## Dataset
The dataset used in this project is sourced from the [IMDB Spoiler Dataset](https://www.kaggle.com/datasets/rmisra/imdb-spoiler-dataset/data) on Kaggle. More information about the dataset and its publication can be found on [Rishabh Misra's website](https://rishabhmisra.github.io/publications/).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
