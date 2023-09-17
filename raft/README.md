# RAFT

[Recurrent All-Pairs Field Transforms for Optical Flow](https://arxiv.org/pdf/2003.12039.pdf)

It is a new deep network architecture for optical flow. RAFT extracts per-pixel features, builds multi-scale 4D correlation volumes for all pairs
of pixels, and iteratively updates a flow field through a recurrent unit that performs lookups on the correlation volumes. RAFT achieves state-
of-the-art performance. On KITTI, RAFT achieves an F1-all error of 5.10%, a 16% error reduction from the best published result (6.10%).
On Sintel (final pass), RAFT obtains an end-point-error of 2.855 pixels, a 30% error reduction from the best published result (4.098 pixels). In
addition, RAFT has strong cross-dataset generalization as well as high efficiency in inference time, training speed, and parameter count. Code
is available at https://github.com/princeton-vl/RAFT.

The command in the repo's README.md:

python evaluate.py --model=models/raft-things.pth --dataset=sintel --mixed_precision

It is not Jupyter notebook friendly. So, some tweaks are make. Please see the RAFT.ipynb file for details.

It requires 2CPUs/4G RAM, with or without GPU.
