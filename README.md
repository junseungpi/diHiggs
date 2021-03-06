# diHiggs
https://arxiv.org/abs/2203.11951
## Abstract
The Higgs potential is vital to understand the electroweak symmetry breaking mechanism, and probing the Higgs self-interaction is arguably one of the most important physics targets at current and upcoming collider experiments. In particular, the triple Higgs coupling may be accessible at the HL-LHC by combining results in multiple channels, which motivates to study all possible decay modes for the double Higgs production. In this paper, we revisit the double Higgs production at the HL-LHC in the final state with two $b$-tagged jets, two leptons and missing transverse momentum. 
We focus on the performance of various neural network architectures with different input features: low-level (four momenta), high-level (kinematic variables) and image-based. 
We find it possible to bring a modest increase in the signal sensitivity over existing results via careful optimization of machine learning algorithms making a full use of novel kinematic variables.

## Model Architecture
### FC
<img src = "https://user-images.githubusercontent.com/98250392/158048281-f16fa09e-bdd4-4caf-9ee6-eff8c37ed8b0.png" width="45%" height="45%">

### CNN
<img src = "https://user-images.githubusercontent.com/98250392/158048813-cfdb09f8-9df8-4efb-a677-58dd3cffe8ca.png" width="80%" height="80%">

### ResNet
<img src = "https://user-images.githubusercontent.com/98250392/157463183-92b6b5f8-7d05-4bd2-b191-b291d6faf605.png" width="50%" height="50%">

### CapsNet
<img src = "https://user-images.githubusercontent.com/98250392/157439084-0ae15ee6-8ef3-4182-9627-2b9d190ed9d6.png" width="80%" height="80%">

### Matrix CapsNet
<img src = "https://user-images.githubusercontent.com/98250392/157445304-dec800fe-f3fe-49fc-8aeb-799d67370935.png" width="70%" height="70%">

### EdgeConv
<img src = "https://user-images.githubusercontent.com/98250392/157439088-cd64dac8-88bc-4ba5-b6e6-43b78433aad2.png" width="60%" height="60%">

### MPNN
<img src = "https://user-images.githubusercontent.com/98250392/157439099-dcc74ff2-f901-4a20-934e-b5d0610fee07.png" width="90%" height="90%">

## Reference
[LeeHuan18/diHiggs](https://github.com/LeeHuan18/diHiggs.git)  
[cezannec/capsule_net_pytorch](https://github.com/cezannec/capsule_net_pytorch.git)  
[yl-1993/Matrix-Capsules-EM-PyTorch](https://github.com/yl-1993/Matrix-Capsules-EM-PyTorch.git)  
[Moeinh77/Matrix-Capsule-Networks-PyTorch](https://github.com/Moeinh77/Matrix-Capsule-Networks-PyTorch.git)
