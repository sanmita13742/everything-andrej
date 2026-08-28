## important resources:
- sum: https://docs.pytorch.org/docs/2.13/generated/torch.sum.html (he used it to explain how to aggregate values across specific tensor dimensions and why maintaining structure with keepdim=True avoids catastrophic **broadcasting** bugs)
- multinomial : https://docs.pytorch.org/docs/2.13/generated/torch.multinomial.html (how integers are sampled out of custom discrete probability distributions)
- Broadcasting semantics https://docs.pytorch.org/docs/2.13/notes/broadcasting.html ( how PyTorch aligns or replicates dimensions implicitly during element-wise mathematical operations)
