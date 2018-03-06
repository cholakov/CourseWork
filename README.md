# Decision Making in Robots and Autonomous Agents(INFR11090): Homework Assignment 2 (Semester 2 -2017/18)


## Relevant Notes:
[OpenAI GYM Tutorial](https://gym.openai.com/docs/)

* Remember to set a seed to ensure that your work is reproducible !


## Requirements

- gym >= 0.9.4
- Python >= 3.6
- Numpy >= 1.13.3
- Matplotlib >= 2.1.1
- Scikit-image >= 0.13.1
- Jupyter
- (Recommended) JupyterLab >= 0.31.0
- ffmpeg (for visualisations)

## Fixes
### Error 1

Reported on a Macbook pro with macOS 10.13.3. 

- If you recieve a **"NOTIMPLEMENTEDERROR:"**, call the internal functions directly by prepending a _ . 
So submarine.reset() becomes submarine.\_reset().
