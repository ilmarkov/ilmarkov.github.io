---
layout: page
title: Gradient Compression Simulator
description: Framework for testing gradient compression integrated into torch.distributed
img: /assets/img/gcomp_sim_logo.png
importance: 2
category:
---

gcomp_sim is a framework for simulating gradient compression methods. It allows to verify the convergence of the training when
any gradient compression technique is applied. The user is to implement the compressor which takes layer gradient and 
modifies it such that the resulting tensor values are equal to the compressed-decompressed values of the original tensor.  

Not public.