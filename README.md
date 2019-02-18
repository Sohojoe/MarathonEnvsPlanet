# MarathonEnvs + Planet

NOTE: does not work yet

Explority implementation of
* MarathonEnvs
* ml-agents
* Planet


### source versions
* MarathonEnvs
* ml-agents = 0.5.1
* Planet (first release)

-----
### Install
* Clone this repro (ideally from a release version)
* [Download](https://github.com/Sohojoe/MarathonEnvsBaselines/releases/tag/v1.0.0) / Unzip prebuilt MatathonEnvs into the `env` folder
* pip installs
```
# PlaNet
pip install -e .
# ml-agents
cd ml-agents
pip install -e .
# gym-unity
cd gym-unity
pip install -e .

```
-----

```sh
python -m planet.scripts.train  \
    --logdir ./summaries \
    --config default \
    --params '{tasks: [hopper_run]}'
```