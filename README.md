# Model-XChain_prototype


# Motivation  

Blockchain has been growing rapidly since its inception. The widespread adoption of blockchain technology has resulted in a diverse and heterogeneous ecosystem, with a wide range of use cases and applications. Therefore, due to the popularity of blockchain, there has been a significant increase in inter-chain communication demands, especially the atomicity of data transfer.  

When it comes to cross-chain transactions, atomicity is very important. Any inconsistency or failure in a single transaction can cause failure in the entire cross-chain business process involving multiple blockchain. Ensuring the atomicity of cross-chain business guarantees that all transactions within the business are either completed successfully, or rolled back to their previous state. And ensuing atomicity in the cross-chain context is a challenging work.

# Overview

Model-Xchain is a model-driven framework for cross-chain business development.
It provides business-level abstractions for modeling cross-chain workflows and supports the automatic generation and execution of Directed Acyclic Graphs (DAGs) to ensure correctness and atomicity across heterogeneous blockchains.

The framework integrates a script-based domain-specific language (DSL), DAG model generation, and DAG-based execution into a unified development process. By abstracting low-level blockchain details and automating dependency management, Model-Xchain reduces manual development effort while supporting atomic cross-chain execution.

