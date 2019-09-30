# awesome-gans

* [Language GANs Falling Short](https://arxiv.org/pdf/1811.02549.pdf)
> Training models which produce both highquality and highly-diverse samples is a central issue of natural language generation (NLG). Typically NLG models are learned under maximum likelihood estimation (MLE). 

> To do so, teacher forcing is used at training but during inference, **samples are instead produced in a free-running mode**, resulting in exposure bias (Bengio et al., 2015; Ranzato et al., 2015). Under the hypothesis that exposure bias is to be blamed for poor sample quality, generative adversarial networks (GANs) have been proposed since these have no discrepancy between training and inference. However, **many of these GAN variants are validated only by improvement to sample quality which ignores the potential loss of sample diversity**. We reiterate the fallacy of quality-only metrics and clearly demonstrate that the well-established technique of reducing softmax temperature can outperform GANs on a quality-only metric. Further, we establish a definitive quality diversity evaluation procedure using temperature tuning over local and global sample metrics. Under this, we find that MLE models consistently outperform the proposed GAN variants over the whole quality-diversity space. 

> Specifically we find: 
> 1) exposure bias appears less an issue than the complications arising from non-differentiable, sequential GAN training; 
> 2) MLE trained models still provide a better quality / diversity trade off than their GAN counterparts, all while being easier to train, easier to cross-validate, and less computationally expensive.1

* [Many Paths to Equilibrium: GANs Do Not Need to Decrease a Divergence At Every Step](https://arxiv.org/pdf/1710.08446.pdf)
