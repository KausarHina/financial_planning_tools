# financial_planning_tools

Financial Planning with APIs and Simulations

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.


## Technologies

This project leverages python 3.7.13 with the following packages:

* [pandas](https://pandas.pydata.org/) - For data analysis


---

## Installation Guide

Before running the application first install the pandas dependency in conda dev environment.

```python

    conda create -n dev python=3.7 anaconda

    python -m ipykernel install --user --name dev

    conda activate dev

    conda install pandas

    conda deactivate 
  
```

---


## Usage

To use the **financial_planning_tools** simply clone the repository and run the **financial_planning_tools.ipynb** with jupyter lab:

```python
    conda activate dev

    jupyter lab

    conda deactivate 
```

Plots of Monte Carlo Simulation

![5-4-monte-carlo-histogram](Images/5-4-monte-carlo-histogram.png)



![5-4-monte-carlo-line-plot](5-4-monte-carlo-line-plot.png)


---

## Contributors

Kausar Hina

---

## License

MIT

