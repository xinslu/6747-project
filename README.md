# Universal Illusions in Multi-Modal Embeddings

To run code on colab, upload the `image_illusion_demo_colab.ipynb` onto colab and connect to a T4 runtime. Then upload a folder called folders.zip with the following folders and files zipped in it:
```
AudioCLIP/
bpe/
dataset_utils.py
evaluate_jpeg.py
imagebind/
utils.py
DiffJPEG/
configs/
evaluate_illusions.py
image/
models.py
```

Then run cell 1 to unzip the folder. Then, run either cell 2-3 for the cosine-similarity and l2 loss or cell 2-4 for Contrastive Loss.
