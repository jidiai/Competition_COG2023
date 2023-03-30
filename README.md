# Competition_COG2023
<img src="imgs/Jidi%20logo.png" width='300px'>  <img src="imgs/cog_logo.png" width='300px'>

This is the source code for [Conference on Games 2023 Football AI Competition](http://www.jidiai.cn/cog_2023/) held by Jidi platform.

This competition has two tracks:

- Track - 1: [5_vs_5 full-game scenario](http://www.jidiai.cn/compete_detail?compete=35)
- Track - 2: [11_vs_11 full-game scenario](http://www.jidiai.cn/compete_detail?compete=36)

Both two tracks start from **June 28th, 2023** to **August 9th, 2023**.

- Competition intro page: http://www.jidiai.cn/cog_2023/
- Jidi tutorial: https://github.com/jidiai/ai_lib/tree/master/assets
- Google Research Football: https://github.com/google-research/football

## Quick Start 
---
You can follow the following steps to run the demo

**Clone the repo**

```bash
git clone https://github.com/jidiai/Competition_COG2023.git
cd Competition_COG2023
```

**Build virtual environment**

```bash
python3 -m venv competition-venv
source competition-venv/bin/activate
python3 -m pip install -e .
```
or 
```bash
conda create -n competition-venv python==3.7.5  #or 3.8
conda activate competition-venv
```

**Install Google Research Football environments**

Please refer to official repo: https://github.com/google-research/football

```bash
cp ./scenarios/11_vs_11_stochastic.py  xxx/gfootball/scenarios/    #copy the scenario scrip to where GRF is installed
```

**Run a game**
```bash
python run_log.py --env football_11_vs_11_stochastic
```

