## To visualize a MEDYAN output file snapshot.traj

### Assuming conda is installed, create a new environment:  
```
conda create --name mayavi python=3.8
```
### then activate the environment with command: 
```
conda activate mayavi
```
### install necessary packages and mayavi:
```
pip install mayavi
pip install PyQt5
pip install ipython
```
### with the environment mayavi activated, start ipython:
```
ipython
```
### In the Ipython interactive command line, go to your working directory (with the animation file and snapshot.traj) and run the animation file:
```
run -i AnimateTrajectory_py3.py   (other .py files are for larger size simulation trajs or tension/actin visualization only)
```
### Visualize the snapshot you are interested in (recommended, 10 as example):
```
show_snapshot(10)
```
### or animate the whole trajectory (may take a while and cause crash of mayavi):
```
anim()
```


