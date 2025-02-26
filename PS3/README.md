# Perception in Robotics: Problem Set 3

## Dependencies

### Required, similar to as in PS2

* python3
* python3-pip
* virtualenv
* dvipng
* ffmpeg

### Python packages, similar to as in PS2
* mrob
* numpy
* matplotlib
* scipy
* tqdm



## Running Code

It's possible to use `virtualenv` or `mini-conda`:

### Create Virtualenv (same as in PS2)

```bash
cd "<project_dir>"
virtualenv -p python3 venv
source venv/bin/activate
```

### Create Conda environment

[Conda Cheat Sheet](https://docs.conda.io/projects/conda/en/latest/_downloads/843d9e0198f2a193a3484886fa28163c/conda-cheatsheet.pdf)

```bash
cd "<project_dir>"
conda create -n "<env_name>" python=3.8
conda activate "<env_name>"
```



### Open created environment
```bash
source venv/bin/activate
```



### Run Code (virtual env must me active)

```bash
cd "<project_dir>"
python run.py -s
```


### Testing and debugging code for each specific filter
```bash
cd "<project_dir>"
python run.py -f graphSlam -n 100
```



### Record video and used the provided data
```bash
cd "<project_dir>"
python run.py -s -f graphSlam -i slam-evaluation-input.npy -m graphSlam.mp4
```
