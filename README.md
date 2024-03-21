# CICIDS2018-Intrusion-Detection-Using-Decision-Trees
This project focuses on implementing intrusion detection using decision trees on the CICIDS2018 dataset. The CICIDS2018 dataset is a comprehensive collection of labeled network traffic data suitable for training and evaluating intrusion detection systems.

## Kaggle Notebook
[Link to Kaggle Notebook](https://www.kaggle.com/code/jvageesh11/cicids2018-using-decision-trees) 

## Kaggle Dataset
[Link to Kaggle Dataset](https://www.kaggle.com/datasets/jvageesh11/cicids2018) 

## Dataset

The dataset contains the following columns:

- **Dst Port**: The destination port number.
- **Protocol**: The network protocol used.
- **Timestamp**: The timestamp of the network traffic.
- **Flow Duration**: The duration of the flow.
- **Tot Fwd Pkts**: Total number of forward packets.
- **Tot Bwd Pkts**: Total number of backward packets.
- **TotLen Fwd Pkts**: Total length of forward packets.
- **TotLen Bwd Pkts**: Total length of backward packets.
- **Fwd Pkt Len Max**: Maximum length of forward packets.
- **Fwd Pkt Len Min**: Minimum length of forward packets.
- **Fwd Pkt Len Mean**: Mean length of forward packets.
- **Fwd Pkt Len Std**: Standard deviation of length of forward packets.
- **Bwd Pkt Len Max**: Maximum length of backward packets.
- **Bwd Pkt Len Min**: Minimum length of backward packets.
- **Bwd Pkt Len Mean**: Mean length of backward packets.
- **Bwd Pkt Len Std**: Standard deviation of length of backward packets.
- **Flow Byts/s**: Flow bytes per second.
- **Flow Pkts/s**: Flow packets per second.
- **Flow IAT Mean**: Mean time between flows.
- **Flow IAT Std**: Standard deviation of time between flows.
- **Flow IAT Max**: Maximum time between flows.
- **Flow IAT Min**: Minimum time between flows.
- **Fwd IAT Tot**: Total time between forward packets.
- **Fwd IAT Mean**: Mean time between forward packets.
- **Fwd IAT Std**: Standard deviation of time between forward packets.
- **Fwd IAT Max**: Maximum time between forward packets.
- **Fwd IAT Min**: Minimum time between forward packets.
- **Bwd IAT Tot**: Total time between backward packets.
- **Bwd IAT Mean**: Mean time between backward packets.
- **Bwd IAT Std**: Standard deviation of time between backward packets.
- **Bwd IAT Max**: Maximum time between backward packets.
- **Bwd IAT Min**: Minimum time between backward packets.
- **Fwd PSH Flags**: Forward packets with PUSH flags.
- **Bwd PSH Flags**: Backward packets with PUSH flags.
- **Fwd URG Flags**: Forward packets with URG flags.
- **Bwd URG Flags**: Backward packets with URG flags.
- **Fwd Header Len**: Length of header in forward packets.
- **Bwd Header Len**: Length of header in backward packets.
- **Fwd Pkts/s**: Forward packets per second.
- **Bwd Pkts/s**: Backward packets per second.
- **Pkt Len Min**: Minimum length of packets.
- **Pkt Len Max**: Maximum length of packets.
- **Pkt Len Mean**: Mean length of packets.
- **Pkt Len Std**: Standard deviation of length of packets.
- **Pkt Len Var**: Variance of length of packets.
- **FIN Flag Cnt**: Number of FIN flags.
- **SYN Flag Cnt**: Number of SYN flags.
- **RST Flag Cnt**: Number of RST flags.
- **PSH Flag Cnt**: Number of PSH flags.
- **ACK Flag Cnt**: Number of ACK flags.
- **URG Flag Cnt**: Number of URG flags.
- **CWE Flag Count**: Number of CWE flags.
- **ECE Flag Cnt**: Number of ECE flags.
- **Down/Up Ratio**: Downstream to upstream ratio.
- **Pkt Size Avg**: Average packet size.
- **Fwd Seg Size Avg**: Average forward segment size.
- **Bwd Seg Size Avg**: Average backward segment size.
- **Fwd Byts/b Avg**: Average forward bytes per bulk.
- **Fwd Pkts/b Avg**: Average forward packets per bulk.
- **Fwd Blk Rate Avg**: Average forward bulk rate.
- **Bwd Byts/b Avg**: Average backward bytes per bulk.
- **Bwd Pkts/b Avg**: Average backward packets per bulk.
- **Bwd Blk Rate Avg**: Average backward bulk rate.
- **Subflow Fwd Pkts**: Subflow forward packets.
- **Subflow Fwd Byts**: Subflow forward bytes.
- **Subflow Bwd Pkts**: Subflow backward packets.
- **Subflow Bwd Byts**: Subflow backward bytes.
- **Init Fwd Win Byts**: Initial forward window size.
- **Init Bwd Win Byts**: Initial backward window size.
- **Fwd Act Data Pkts**: Forward packets with actual data.
- **Fwd Seg Size Min**: Minimum segment size in forward packets.
- **Active Mean**: Mean active time.
- **Active Std**: Standard deviation of active time.
- **Active Max**: Maximum active time.
- **Active Min**: Minimum active time.
- **Idle Mean**: Mean idle time.
- **Idle Std**: Standard deviation of idle time.
- **Idle Max**: Maximum idle time.
- **Idle Min**: Minimum idle time.
- **Label**: The intrusion type label.

**Dataset Source**: [CICIDS2018 Dataset](https://www.unb.ca/cic/datasets/ids-2018.html)

## Results

The model achieved an accuracy of 100%, with only 11 misclassified examples.

![image](https://github.com/Vageesh-Jayaraman/CICIDS2018-Intrusion-Detection-Using-Decision-Trees/assets/143870355/6cc56c77-93dc-4e98-b53d-25e3039d0d2b)


## Credits

The CICIDS2018 dataset used in this project is provided by the University of New Brunswick (UNB) - Canadian Institute for Cybersecurity (CIC).

