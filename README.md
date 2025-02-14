# Hi, I'm Samarpan Chakraborty 👋

## 🎓 About Me

I am a data scientist pursuing Ph.D. in Mechanical Engineering at the University of Maryland with a strong background in machine learning, deep learning, time series analysis and numerical methods. My research is primarily focused at analyzing time series data containing wave signatures, with an aim to carry out detection and forecasting of anomalies in the future. I am passionate about leveraging data-driven insights to solve real-world problems.

- 🔬 **Research Interests:** Machine Learning, Deep Learning, Graph Neural Networks, NLP, Numerical Methods, Extreme Wave Analysis
- 📊 **Technical Skills:** Supervised machine learning, Unsupervised machine learning, Statistical Analysis, Data visualization, Data assimilation, Cloud Computing (AWS)
- 🌍 **Programming:** Python, SQL, MATLAB, C++
- 🛠  **Software & Tools:** PyTorch, Tensorflow, Keras, pandas, Matplotlib, Seaborn, MySQL, HuggingFace, CUDA, Tableau, JupyterLab, Keras, Scikit-Learn
- 💼 **Seeking:** Data Scientist, Machine Learning Engineer, or AI Researcher roles

## 📂 Projects

### 1. 🌊 **Rogue wave forecasting using graph neural networks and LSTM**
**Description:** This project explores the detection of rogue waves through a combination of graph neural networks and recurrent neural networks. The dataset involves time series data, collected from wave buoys throughout the world. The project looks at two facets:
1. **Temporal rogue wave forecasting:** Time series windows of varying lengths have been extracted from wave buoy data procured via the [CDIP buoys](https://cdip.ucsd.edu/m/stn_table/). The aim was to forecast the occurrence of a rogue wave within a definite time horizon in the future, given a time window of some duration being input to the model. A graph isomorphism model is trained on an equal number of instances leading to rogue and non-rogue waves.
1. **Spatio-temporal rogue wave forecasting:** Wave time series data from a set of localized buoys, drawn from the same set of buoy data have been utilized to train a combination of graph convolutional network and a LSTM with graph edges constructed using the distance between the buoys. The graph convolutions are used for spatial mapping while the LSTM network utilizes the graph learnings for time series prediction. 
- **Technologies:** Python, Pandas, PyTorch Geometric, NetworkX, PyTorch 
- **Key Highlights:** Forecasting of rogue waves over a **10-minute horizon window** led to more than **71% accuracy on the largest rogue waves**, which has not been achieved before.
- [GitHub Repository/Notebook Link]

### 2. 🌊 Time Series Imputation using CNNs, LSTMs & Singular Spectrum Analysis(SSA)
**Description:** This project investigates multiple time series missing value imputation methods for ocean wave buoy measurements. The study compares different models by filling continuous gaps of varied sizes, leveraging a wave model that decomposes wave elevation into rapid oscillations with slowly varying amplitudes. The imputation approaches utilize these amplitudes either directly in a CNN+LSTM network leveraging an attention mechanism to impute missing values or via surface elevation reconstruction for SSA. The research also explores the effect of modifying the peak regularization factor in the wave model on imputation accuracy.
- **Technologies:** PyTorch, MATLAB, Python, JupyterLab, Seaborn
- **Skills:** Wave model decomposition, SSA, Deep neural networks, Attention mechanism, Data visualization
- **Key Highlight:** **The attention leveraged CNN + LSTM model outperforms baseline and other models** for imputing varied gap sizes in the time series **ranging till 5 minutes**, while SSA excels for smaller gaps, validating the effectiveness of both approaches.
- [GitHub Repository/Notebook Link]

For more projects, check my [GitHub repositories](https://github.com/SamarpanChakraborty97).

## 📄 Publications & Research
- [**Missing values imputation in ocean buoy time series data**](https://doi.org/10.1016/j.oceaneng.2024.120145), Ocean Engineering, 2025
- **Extreme Waves: Data-driven Approaches and Forecasting**, Nonlinear Dynamics and Vibrations: Applications in Engineering, 2025 (Accepted for publication)
- [**Simulations of modulated plane waves using weakly compressible smoothed particle hydrodynamics**](https://link.springer.com/article/10.1007/s00366-023-01894-9), Engineering With Computers, 2023
- [**Wave Propagation Studies in Numerical Wave Tanks with Weakly Compressible Smoothed Particle Hydrodynamics**](https://www.mdpi.com/2077-1312/9/2/233)), Journal of Marine Science and Engineering, 2021

## 💬 Let's Connect!
- 📧 Email: schakr18@umd.edu
- 🔗 LinkedIn: [samarpanchakraborty](https://www.linkedin.com/in/samarpanchakraborty/)

Feel free to check out my repositories and reach out if you’d like to collaborate!

---

⭐ **If you like my work, consider starring this repo!** ⭐
