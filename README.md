# STAT490

Login to WandB and add your wandb id to src/configs/wandb_config.py
Move into src, run python launch_benchmarks/launch_benchmarks.py. This will create a csv with the wandb sweep to run, and save it in src/launch_benchmarks/sweeps/all_benchmarks_medium.csv.
Run each sweep by running wandb agent <USERNAME/PROJECTNAME/SWEEPID> in src.
Move into analyses, run R code.
The numerical results are in the analyses/plot directory.
