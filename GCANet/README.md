Gated Context Aggregation Network for Image Dehazing and Deraining
=======
## Getting Started

This paper is implemented with Pytorch framework.

Demo
----

Directly put all your test images under one directory. Then run:

```bash
python test.py --task [dehaze | derain] --gpu_id [gpu_id or -1 for cpu] --indir [input directory] --outdir [output directory]
```