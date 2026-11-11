# CS-Drift-Dataset
This repository provides the processed CS-Drift dataset used in the experiments of our manuscript.

## Dataset structure

- `Train/`: training set
- `Val/`: validation set
- `Test_A/`: in-distribution test set
- `Test_B/`: temporal drift scenario
- `Test_C/`: version-related drift scenario
- `Test_D/`: TLS 1.3 compound drift scenario

For each split:

- `*_x_cs.pkl`: processed model inputs

- `*_y_cs.pkl`: corresponding labels

  

## Raw PCAP Files

`CS_Drift_raw_pcap.zip` contains the raw PCAP files from which the processed CS-Drift dataset was constructed. IP addresses and port numbers have been anonymized, and all TLS payloads remain encrypted.

## Notes

The repository contains the processed and anonymized data used for model training and evaluation. Raw network traffic files are not publicly released because they may contain security-sensitive information.
