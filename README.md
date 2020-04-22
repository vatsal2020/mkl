# Choosing the Samples with Lowest Loss Makes SGD Robust     
 
    Authors: Vatsal Shah, Xiaoxia Wu, Sujay Sanghavi
    from UT Austin
Link: https://arxiv.org/abs/2001.03316 
#### In this repository, we provide the code for the experiments described in Section 6 of the paper for neural networks.
## Abstract
The presence of outliers can potentially significantly skew the parameters of machine learning models trained via stochastic gradient descent (SGD). In this paper we propose a simple variant of the SGD method: in each step, first choose a set of $k$ samples, then from these choose the one with the smallest current loss, and do an SGD-like update with this chosen sample. Vanilla SGD corresponds to $k=1$, i.e. no choice; $k\geq 2$ represents a new algorithm that is however effectively minimizing a non-convex surrogate loss. Our main contribution is a theoretical analysis of the robustness properties of this idea for machine learning problems which are sums of convex losses; these are backed up with synthetic and neural network experiments.

## Citation
If you use this method or this code in your paper, then please cite it (To appear in AISTATS 2020):

```
@article{shah2020choosing,
  title={Choosing the Sample with Lowest Loss makes SGD Robust},
  author={Shah, Vatsal and Wu, Xiaoxia and Sanghavi, Sujay},
  journal={arXiv preprint arXiv:2001.03316},
  year={2020}
}
```
