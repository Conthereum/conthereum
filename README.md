# Conthereum

## Introduction

Blockchain technology has revolutionized decentralized computation, providing high security through transparent cryptographic protocols and immutable data. However, the Blockchain Trilemma—an inherent trade-off between security, scalability, and performance—limits computational efficiency, resulting in low transactions-per-second (TPS) compared to conventional systems like Visa or PayPal.

To address this, we introduce **Conthereum**, a novel concurrent blockchain solution that enhances multi-core usage in transaction processing through a deterministic scheduling scheme. It reformulates smart contract execution as a variant of the Flexible Job Shop Scheduling Problem (FJSS), optimizing both time and power consumption.

Conthereum offers the most efficient open-source implementation compared to existing solutions. Empirical evaluations based on Ethereum, the most widely used blockchain platform, show near-linear throughput increases with available computational power. Additionally, an integrated energy consumption model allows participants to optimize power usage by intelligently distributing workloads across cores.

This solution not only boosts network TPS and energy efficiency, offering a scalable and sustainable framework for blockchain transaction processing, but also opens new avenues for further optimizations in Ethereum. Furthermore, it is adaptable for broader applications in other blockchain infrastructures.

**Note:** Some repositories in the Conthereum project are temporarily private and will be made public as soon as the related papers are officially published.

## Repositories

Below is the list of repositories in the Conthereum project, each focusing on different aspects of concurrency in blockchain transaction scheduling:

1. **[scheduler-greedy](https://github.com/Conthereum/scheduler-greedy)**: The best-performing greedy algorithm scheduler for blockchain transaction scheduling.
2. **[conflict-detector-static-analysis](https://github.com/Conthereum/conflict-detector-static-analysis)**: Static analysis for detecting conflicts in smart contract execution.
3. **[sok-concurrency-tools](https://github.com/Conthereum/sok-concurrency-tools)**: Tools from the survey **SoK: Concurrency in Blockchain**, including methodologies and utilities for concurrency in blockchain platforms.

## Scheduler Benchmarking

To explore various scheduling algorithm implementations and see how the **Greedy Algorithm** outperforms the others, follow the link to the **[scheduler-benchmarking](https://github.com/Conthereum/scheduler-benchmarking)** repository, where benchmarking results are presented for multiple scheduling approaches.

## Citation

If you use any of the repositories in this project, please cite the following papers:

### Conthereum Paper:

```bibtex
@inproceedings{Conthereum_Zareh_2025,
  author = {Zareh Chahoki, Atefeh and Herlihy, Maurice and Roveri, Marco},
  title = {Conthereum: Concurrent Ethereum Optimized Transaction Scheduling for Multi-Core Execution},
  year = {2025},
  isbn = {-},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {-},
  doi = {-},
  booktitle = {The 37th ACM Symposium on Parallelism in Algorithms and Architectures},
  pages = {349--358},
  numpages = {22},
  location = {Portland, Oregon, USA},
  series = {SPAA '25}
}

@inproceedings{Extended_Conthereum_Zareh_2025,
  author = {Zareh Chahoki, Atefeh and Herlihy, Maurice and Roveri, Marco},
  title = {Extended Conthereum: Advanced Multi-Core Transaction Scheduling with Enhanced Evaluations},
  year = {2025},
  isbn = {-},
  publisher = {Beyond the Chain: Workshop on Next-Generation Distributed Ledger Technologies (NextGenDLT)},
  booktitle = {The 3rd Beyond the Chain Workshop on Next-Generation Distributed Ledger Technologies},
  location = {Pisa, Italy},
  series = {NextGenDLT'25}
}

@article{Survey_Zareh_2025,
  author = {Atefeh Zareh Chahoki, Maurice Herlihy, Marco Roveri},
  title = {SoK: Concurrency in Blockchain, A Systematic Literature Review and Unveiling a Misconception},
  journal = {ACM Computing Surveys},
  year = {2025}
}
```


## Maintenance

For maintenance and inquiries related to this repository, please contact:

**Atefeh Zareh**  
GitHub ID: [Atefeh-Zareh](https://github.com/Atefeh-Zareh)

Feel free to reach out for any questions or issues regarding the project.
