# Detectron
..Back to original Repo [DETECTRON](https://github.com/facebookresearch/Detectron)

#Detectron for Faster R-CNN using Pascal 2007

To train Faster R-CNN using Pascal 2007, follow the instructions on installing the Pascal dataset from [here](https://github.com/facebookresearch/Detectron/blob/master/lib/datasets/data/README.md).

Once you have trained with pascal use infer_simple.py to evaluate your own images.

python2 infer_simple.py --cfg yaml_file.yaml \
--output-dir /some/dir \
--wts /trained/model_final.pkl \
--ds voc \
/path/to/images


