# Master thesis

The main idea is the implemantation of a framework that uses semantic and deep learning algorithms to detect anomalies in event logs. This framework includes:
- Both synthetic and real-world event logs 
- Word2vec and act2vec as feature extraction
- LSTM-autoencoder as deep learning algorithm

The performace of LSTM-autoencoder is compared to three ML algorithms LOF, OSVM, and SVM

In the end, an approach for anomaly classification is implemented.
## Requirements

- Python 3 [Link](https://www.python.org/downloads/)
- Anaconda [Link](https://www.anaconda.com/products/distribution)

## Project directories 

    .
    ├── datasets                # Synthetic and real-world event logs
    │   ├── first_group_of_synthetic_logs
    │   ├── second_group_of_synthetic_logs
    │   └── real_world_logs
    ├── results                 # Results in excel file
    ├── helpers                 # Helper scripts to pre-process log files
    ├── impl                    # Main implementation scripts
    ├── LICENSE
    └── README.md

