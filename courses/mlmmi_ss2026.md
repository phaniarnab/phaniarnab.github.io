# MLMMI - Machine Learning Model Management and Inference [SoSe 2026]

This advanced course explores the system and data management challenges in managing and serving machine learning (ML) models. The lifecycle of an ML model extends far beyond training.

The course begins with recapping standard ML pipelines up to the training stage and then shifts focus to the post-training workloads. Students will be introduced to foundational frameworks for model management, where trained models are treated as core data artifacts. Topics include data management techniques and optimizations such as model selection, versioning, lineage tracking, metadata management, and model monitoring.

Building on these foundations, students will explore the architectures of modern model serving systems for both classical models and large language models (LLMs), along with performance optimizations such as dynamic batching, model compilation, and resource-efficient inference execution. Finally, the course discusses ML agents as an emerging workload.

Throughout the course, students will engage with state-of-the-art research on inference and model management. Through a combination of seminal research papers and hands-on projects, students will gain a comprehensive understanding of the entire ML lifecycle beyond training, preparing them for both academic research and real-world system design.

- **Where**: E-N 189 (lectures) and MAR 0.001 (exercises)
- **When**: Wednesday, 16:15 - 17:45 (lectures) and Monday, 16:15 (exercises). First lecture: April 15, 16:15


> Note
>
> The outline below is tentative. It will evolve as we teach.

### Lecture 1: Intro and Logistics [April 15]
- Recap of ML pipeline stages
- [Stratum](https://arxiv.org/pdf/2603.03589) system overmiew

## Part1: ML Deployment
  
### Lecture 2: ML Platforms and Deployment [April 22]
- MLOps
- Readings: TFX
  
### Lecture 3: Model Selection Systems
- Model selection systems
- Transfer learning
- Readings: Ease.ml, Cerebro
  
### Lecture 4: Model Registry and Versioning
- Model versioning
- Feature stores
- Readings: ModelDB, MLFlow

## Part2: ML Serving
 
### Lecture 5: ML Serving Systems
- Traditional model serving
- In-database serving
- Readings: Clipper

### Lecture 6: LLM Serving

### Lecture 7: LLM Serving Optimizations

### Lecture 8: Model Monitoring and MLE Agents

## Programming Assignments
TBD

## Projects
The majority of the course grade will come from a group project. The projects are designed to be challenging and research-oriented and will be implemented in stratum, a system infrastructure for large-scale agent-centric ML workloads. Specific project topics will be announced in the coming weeks.  
Paper: https://arxiv.org/pdf/2603.03589  
Code: https://github.com/deem-data/stratum

