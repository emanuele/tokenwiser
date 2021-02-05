We noticed that a lot of benchmarks relied on heavy-weight tools while they did not 
check if something more lightweight would also work. In this package we list tools 
that will help you do lightweight benchmarks using three packages: 

- scikit-learn
- spaCy
- vowpal wabbit 

The idea is that maybe we don't need language models for basic tasks. Maybe we just need
to add some features from spaCy in scikit-learn. Conversely, maybe we can add some simple 
benchmark models to spaCy by leveraging scikit-learn and vowpal wabbit. 

This is what we hope to explore in this package.

ps. If you're looking for a tool that can add language models to scikit-learn pipelines as 
a benchmark you'll want to explore another tool: [whatlies](https://rasahq.github.io/whatlies/tutorial/scikit-learn/).