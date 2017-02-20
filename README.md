# DL-workshop-2017

A lightning-fast introduction to some concepts in ML/DL

## Instructions:

- Connect to Moria
- Clone this repository in a folder, let's say `dl_workshop`
- Type `module purge` to remove all your modules
- Type `module load pythonML/3.2-goolf-1.5.14-NX-python-2.7.11`
- Type module load `ipython/5.0.0-goolf-1.5.14-NX-python-2.7.11`
- Go into the `dl_workshop` folder
- Type `ipython notebook --no-browser --port=8889`. This will launch the Jupyter notebook server on port 8889
- On your local system ssh into the remote system performing port forwarding typing: `ssh -N -f -L localhost:8888:localhost:8889 your_5_2_1@moria`
- Start your browser and point it to `http://localhost:8888/`

You should be able to see the notebook. Click on it to open it.

When you are done, stop the Notebook, the Jupyter server, and remember to close the connections on your local machine. To find their PIDs type `ps aux | grep localhost:8889` and then kill them manually with `kill -15 pid_number`.
