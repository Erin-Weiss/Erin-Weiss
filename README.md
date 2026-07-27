[![Header](https://raw.githubusercontent.com/Erin-Weiss/Erin-Weiss/main/erin-weiss-banner.png)](https://github.com/Erin-Weiss)

---

## About Me

I build tools people can run and trust.

My deepest work is in machine learning systems and the infrastructure to run them, including a CatBoost model that predicts used-car prices within ~$1,300 at the median across 243k vehicles, served via a FastAPI endpoint with Docker, Kubernetes, and automated testing. Around that sit data pipelines, geospatial analysis, and client-facing applications, including a live tool that searches 127k parcel records and ships an assumptions log with every run so the client can see how the answer was reached.

Before this I spent several years as a Director of Strategic Planning, making calls off tools whose limits I could not see. That is where I learned to build for the people who inherit the tool, not the person who wrote it.

**Explore my projects:** [Erin Weiss Portfolio](https://erin-weiss.github.io/index.html)  
**View my résumé:** [Download Here](https://drive.google.com/file/d/191c2Msghk1dNXZPXrVh-ex0RWGSA3HLl/view?usp=sharing)  
**Reach me at:** erin.michele.weiss@gmail.com

---

## Featured Projects

### [Used Car Price Prediction](https://github.com/Erin-Weiss/used-car-price-prediction) — Model Development

Predicts used-car listing prices within ~$1,300 at the median across 243k vehicles, 29 manufacturers, and 5,600+ model variants. Compared Ridge, CatBoost, and FT-Transformer architectures with reproducible experiment management and versioned artifacts.

`Python` · `CatBoost` · `scikit-learn` · `TensorFlow` · `Keras` · `pandas` · `Quarto`

### [Used Car Price Prediction API](https://github.com/Erin-Weiss/used-car-price-api) — Production Deployment

Takes the CatBoost model from Part 1 and ships it as a production API: request validation, fuzzy input matching, multi-stage Docker builds, Kubernetes orchestration with autoscaling, Prometheus + Grafana monitoring, and CI/CD via GitHub Actions.

`FastAPI` · `Docker` · `Kubernetes` · `GitHub Actions` · `Prometheus` · `Grafana` · `pytest`

### [Demolition Neighbor Notification](https://github.com/Erin-Weiss/stl-demo-notify) — Geospatial Tool ([Live App](https://stl-demo-notify.streamlit.app/))

Turns a contractor's demolition site list into a complete neighbor notification package. Searches 126,958 St. Louis parcels against 500 ft buffers measured from each site's boundary, returning 1,636 addresses across a 30-site project and flagging 134 parcels whose assessor records contradict themselves for field verification. Ships as both a Streamlit app and a CLI running the identical pipeline.

`Python` · `GeoPandas` · `Folium` · `Streamlit` · `GeoParquet` · `pytest` · `ruff`

### [Reinforcement Learning](https://github.com/Erin-Weiss/reinforcement-learning) — Agent Optimization

Implements RL algorithms to optimize a mobile robot's warehouse path. Covers exploration vs. exploitation, policy optimization, hyperparameter tuning, and reward shaping.

`Python` · `NumPy` · `pandas` · `Matplotlib`

### [Real Estate Analysis](https://github.com/Erin-Weiss/R-Real-Estate-Project) — Statistical Modeling in R

Analyzes U.S. housing trends (2016–2022) with a multiple linear regression model explaining ~95% of price variation.

`R` · `tidyverse` · `ggplot2`

> **See all projects →** [erin-weiss.github.io](https://erin-weiss.github.io/index.html)

---

### Languages and Tools

<p align="left">
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=py" alt="Python" width="40" height="40"/>
  </a>
  <a href="https://www.r-project.org" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=r" alt="R" width="40" height="40"/>
  </a>
  <a href="https://scikit-learn.org" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=scikitlearn" alt="scikit-learn" width="40" height="40"/>
  </a>
  <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=tensorflow" alt="TensorFlow" width="40" height="40"/>
  </a>
  <a href="https://keras.io" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/keras/keras-original.svg" alt="Keras" width="40" height="40"/>
  </a>
  <a href="https://fastapi.tiangolo.com" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=fastapi" alt="FastAPI" width="40" height="40"/>
  </a>
  <a href="https://www.docker.com" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=docker" alt="Docker" width="40" height="40"/>
  </a>
  <a href="https://kubernetes.io" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=kubernetes" alt="Kubernetes" width="40" height="40"/>
  </a>
  <a href="https://prometheus.io" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=prometheus" alt="Prometheus" width="40" height="40"/>
  </a>
  <a href="https://grafana.com" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=grafana" alt="Grafana" width="40" height="40"/>
  </a>
  <a href="https://github.com/features/actions" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=githubactions" alt="GitHub Actions" width="40" height="40"/>
  </a>
  <a href="https://pandas.pydata.org" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/>
  </a>
  <a href="https://numpy.org" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="NumPy" width="40" height="40"/>
  </a>
  <a href="https://geopandas.org" target="_blank" rel="noreferrer">
    <img src="https://cdn.simpleicons.org/geopandas/139C5A" alt="GeoPandas" width="40" height="40"/>
  </a>
  <a href="https://matplotlib.org" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" width="40" height="40"/>
  </a>
  <a href="https://jupyter.org" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" alt="Jupyter" width="40" height="40"/>
  </a>
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" width="40" height="40"/>
  </a>
  <a href="https://www.getdbt.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/gilbarbara/logos/main/logos/dbt-icon.svg" alt="dbt" width="40" height="40"/>
  </a>
  <a href="https://www.mysql.com" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=mysql" alt="MySQL" width="40" height="40"/>
  </a>
  <a href="https://www.sqlite.org" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=sqlite" alt="SQLite" width="40" height="40"/>
  </a>
  <a href="https://streamlit.io" target="_blank" rel="noreferrer">
    <img src="https://cdn.simpleicons.org/streamlit/FF4B4B" alt="Streamlit" width="40" height="40"/>
  </a>
  <a href="https://git-scm.com" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=git" alt="Git" width="40" height="40"/>
  </a>
  <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=bash" alt="Bash" width="40" height="40"/>
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=html" alt="HTML5" width="40" height="40"/>
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=css" alt="CSS3" width="40" height="40"/>
  </a>
  <a href="https://www.figma.com" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=figma" alt="Figma" width="40" height="40"/>
  </a>
</p>

---

### Connect with Me

<p align="left">
  <a href="https://github.com/Erin-Weiss" target="blank">
    <img align="center" src="https://skillicons.dev/icons?i=github" alt="GitHub" height="40" width="40" />
  </a>
  <a href="https://linkedin.com/in/erinweiss3" target="blank">
    <img align="center" src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" height="40" width="40" />
  </a>
</p>
