# robot-colosseum
It's modified version.
# Usage
Replace the following files:
```
$HOME/robot-colosseum/colosseum/tools/dataset_generator.py
$HOME/robot-colosseum/colosseum/rlbench/extensions/task_environment.py
#anaconda3
$HOME/anaconda3/envs/colo/lib/python3.9/site-packages/rlbench/backend/scene.py
#or miniconda
$HOME/miniconda3/envs/colo/lib/python3.9/site-packages/rlbench/backend/scene.py
```
# Workflow
change .yaml & collect_dataset.sh parameters!!!
```
export LD_PRELOAD=/usr/lib/x86_64-linux-gnu/libffi.so.7
./collect_dataset.sh
```
