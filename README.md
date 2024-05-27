# appa-real

The machine predictions stored in ```machine_predicions/``` are computed by multi-layer neural network (MLP) trained on image representations extracted via the FaRL architecture  [[Paplham et al 2024]](https://arxiv.org/abs/2307.04570). The FaRL representation is initially pre-trained on the 20M LAION database of facial image-text pairs. Subsequently, the MLP undergoes fine-tuning using the training and validation subsets of the APPA-REAL database. Two models are employed: one fine-tuned and evaluated on images annotated with real age and the other on images annotated with apparent age. 




