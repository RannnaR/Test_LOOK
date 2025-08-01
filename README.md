# Blink Behavior and Environmental Data Analysis

This repository contains a collection of Jupyter notebooks focused on the synchronization, analysis, and statistical processing of blink behavior metrics and environmental data collected during experimental studies. The analyses include Blink Rate (BR), Mean Blink Interval (MBI), and other physiological and environmental factors.

## Contents

### Synchronization

* **Synchro\_BR.ipynb**: Synchronizes blink rate (BR) data from the eye tracker Tobii Pro Spectrum and EOG signal.
* **Synchro\_MBI.ipynb**: Synchronizes mean blink interval (MBI) data across Tobii and EOG.

### Data Analysis

* **BR\_tracer.ipynb**: Analyzes blink rate data, extracting relevant metrics and patterns.
* **MBI\_tracer.ipynb**: Processes and analyzes mean blink interval data, identifying trends and significant features.
* **PBR\_tracer.ipynb**: Analyzes partial blink rate (PBR) data, providing insights into the correlation between dry eye metrics and the eye openness.

### Environmental Analysis

* **environment\_tracer.ipynb**: Processes and analyzes environmental data affecting blink behavior, including variables such as humidity and temperature.
* **Analysis\_openness.ipynb**: Examines eye openness data to correlate with blink behavior metrics.
* **Analysis\_openness\_function.ipynb**: Contains reusable functions used within the eye openness analysis.

### Statistical Analysis

* **stat\_analysis.ipynb**: Performs statistical analyses to investigate relationships between blink metrics and environmental factors, and to determine the significance of observed patterns.

## Usage

To run these notebooks, ensure your Python environment contains necessary packages:

```bash
pip install numpy pandas matplotlib scipy seaborn
```

Open the notebooks in Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

## Data Structure

Ensure your datasets are appropriately structured and placed within the designated folders or directories expected by each notebook.

## Contact

For further information or inquiries, please contact \[Zhuoran YU] at \[[zhuoran.yu@etu.unistra.fr](mailto:zhuoran.yu@etu.unistra.fr)].
