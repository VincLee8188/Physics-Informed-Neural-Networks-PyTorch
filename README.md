# Physics-Informed-Neural-Networks
I tried to construct the Pytorch-version implementation of the physics informed neural networks and successfully reproduced the numerical results in [Physics Informed Deep Learning (Part I): Data-driven Solutions of Nonlinear Partial Differential Equations](https://arxiv.org/abs/1711.10561).

The author's original implementation in TensorFlow can be found here:
* [TensorFlow](https://github.com/maziarraissi/PINNs)

As it was put in the article, the resulting neural networks form a new class of data-efficient universal function approximators that naturelly encode any underlying physical laws as prior information. The most inspiring idea I acquired from this article is encoding structured information gained by prior knowledge into a learning algorithm, which can significantly relieve data acquisition pressure and reduce training time. In addition, deep neural networks' capability as universal function approximators is well demonstrated in this task, for they are able to directly tackle nonlinear problems without the need for committing to any prior assumptions, linearization, or local time-stepping.
