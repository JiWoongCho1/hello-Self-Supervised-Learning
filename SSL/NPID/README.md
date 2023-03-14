## Unsupervised Feature learning via Non-Parameteric Instance Discrimination



The rise of deep neural networks, especially CNNs, has led to several breakthroughs in computer vision benchmarks. Most successful models are trained via supervised learning, which requires large datasets. that are completely annotated for a specific task. However, obtaining annotated data is often very costly or even infeasible n certain cases. Next figure show that an image from class leopard is rated much higher by class jaguar rathr than by class bookcase. Such observations reveal that a typical discriminative learning method can automatically discover apparent similarity among semantic categories, without being explicitly guided to do so. In other words, apparent similarity is learned not from semantic annotations, but from the visual data themselves. If they learn to discriminate between individual instances, without any notion of semantic categories, authors think that they may end up with a representation that caputures apprent similarity among instances, just like how class-wise supervised learning still retains apprent similarity among classes.

(figure1)

Their novel unsupervised feature learning approach is instance-level discrimination. They treat each image instance as a distinct class of its own and train a classfier to distinguish between individual instance classes.

(figure2)

