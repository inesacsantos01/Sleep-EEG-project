# Exploration, visualization and classification of EEG signals 
This project analyzes EEG (electroencephalogram) signals from a PhysioNet dataset with the goal of identifying and classifying brain activity patterns such as alpha, beta, theta, and delta waves

# Project Structure
sleep-eeg-project/
├── data/
│   └── SC4001E0-PSG.edf     
│   └── SC4002EC-Hypnogram    
├── EEG.ipynb              
├── README.md                 
└── requirements.txt          

# Objective
* Load EEG data from a night's sleep
* Filter and visualize the signal
* Calculate spectral power for different bands (alpha, theta, delta, beta)
* Associate patterns with states of consciousness

# How to Run 

```bash
git clone https://github.com/inesacsantos01/sleep-eeg-project.git
cd sleep-eeg-project
pip install -r requirements.txt
jupyter notebook EEG.ipynb
```

---
## Author 
 Inês Santos
