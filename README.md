<div align="center">    
 
# Anomaly Candidate Extraction and Detection for automatic quality inspection of metal casting products using high-resolution images     

[![DOI](http://img.shields.io/badge/DOI-10.1016/j.jmsy.2023.02.007-B31B1B.svg)](https://doi.org/10.1016/j.jmsy.2023.02.007)
[![Pages](https://img.shields.io/badge/Pages-229:241-blue.svg)](https://www.sciencedirect.com/science/article/pii/S0278612523000316)
[![Volume](https://img.shields.io/badge/Volume-67-4b44ce.svg)](https://www.sciencedirect.com/journal/journal-of-manufacturing-systems/vol/67)
[![Journal](https://img.shields.io/badge/Journal-JMS-red.svg)](https://www.sciencedirect.com/journal/journal-of-manufacturing-systems)

[//]: # ([![Publisher]&#40;https://img.shields.io/badge/Publisher-Elsevier-4b44ce.svg&#41;]&#40;https://www.sciencedirect.com/journal/journal-of-manufacturing-systems/vol/67&#41;)
   
</div>

This repository provides a summary of the *__ACED__* method presented in our
_Journal of Manufacturing Systems_ 2023 paper: __Anomaly Candidate Extraction and Detection for automatic quality inspection of metal casting products using high-resolution images__.

You find a paper at 
[https://www.sciencedirect.com/science/article/pii/S0278612523000316](https://www.sciencedirect.com/science/article/pii/S0278612523000316).

## Abstract
> This paper proposes an AI-based detection method called ACED (Anomaly Candidate Extraction and Detection) that can find tiny defects efficiently by inspecting the surface of cast manufactured products through high-resolution images. A major challenge is to minimize false detection to a level competent to skilled human inspectors. Also, high-resolution imaging is necessary to capture meaningful information about tiny flaws, but it may cause overfitting of AI models and increase computational burdens. We have designed ACED in a few steps to overcome the challenges: first, we create image partitions using factory-defined inspection area information and create regions of interest containing the most abnormal spots found by a convolutional autoencoder. Next, we filter out regions with minor flaws using the specification of significant flaws, where the information is available from a production line. Finally, we train an ensemble of convolutional neural networks to classify the defect candidates as normal or defective. We implemented and tested the proposed method ACED for two cast-manufactured automobile parts in a test production line of our collaborator’s factory. Our experimental results showed that ACED was particularly better in reducing false positive detection, outperforming other AI-based detection methods by $\times 10.5 \sim \times 43.0$ in terms of accurate rates and $\times 5.3 \sim \times 18.2$ in F1-scores, depending on the tested products. Also, ACED was competent to human inspectors, achieving $\times 1.9 \sim \times 4.0$ performance gains in F1-scores. We also provide analyses of execution time, resource utilization, and inspection time reduction of factory workers, showing the potential of ACED to be used in actual production lines.


### Citation   
```
@article{jung2023anomaly,
    title={Anomaly Candidate Extraction and Detection for automatic quality inspection of metal casting products using high-resolution images},
    author={Byeonggil Jung and Heegon You and Sangkyun Lee},
    journal={Journal of Manufacturing Systems},
    volume={67},
    pages={229-241},
    year={2023},
    publisher={Elsevier},
    issn={0278-6125},
    doi={https://doi.org/10.1016/j.jmsy.2023.02.007},
    url={https://www.sciencedirect.com/science/article/pii/S0278612523000316}
}
```   