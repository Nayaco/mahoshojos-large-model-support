# Mahoshojo's Large Model Support

Mahoshojo's Large Model Support(MLMS) based on IBM PyTorch Large Model Support(LMS).

IBM PyTorch Large Model Support(LMS) is no longer update for last 3 years, though DNN researches still need a framework support low level editable data offloading and checkpointing which are seperatly well implemented by LMS and Dynamic Tensor Rematerization(DTR).

Mahoshojo's Large Model Support(MLMS) is to merge offloading and checkpointing together and make compatible with pytorch-1.12 or so.

## Installing Mahoshojo's Large Model Support

```
git clone https://github.com/pytorch/pytorch
cd pytorch
git checkout v1.12.0
git am /mahoshojos-large-model-support/patches/pytorch_v1.12.0_large_model_support.patch
```