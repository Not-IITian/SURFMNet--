# Neurips 2020: Weakly-supervised-Deep-Functional-map for shape Matching
 Paper here: https://arxiv.org/abs/2009.13339

# Requirements:
--Tensorflow 1.x version

--Please download the tf_ops and utils folder from pointnet++ github repository and compile tf_ops according to the instructions provided there.

# Running the code
Our source code then contains 3 files:
1) train_test.py
2) model.py
3) loss.py: contains also the implementation of halimi et al. loss and also supervised loss of GeomFmap.

By default, running train_test.py with suitable data runs our method and replicates all results in main paper. 

To include supervised loss of Donati et al., please replace E5 (currently set to 0) with sup_penalty_surreal. 

Similarly, to include halimi et al. unsupervised loss, please replace E5 with pointwise_corr_layer.


# Weakly Aligned Data
Faust remesh aligned: https://drive.google.com/file/d/1C-9GFsTl5xwa0RUmC_m1nnj87QUguh6j/view?usp=sharing

Scape remesh aligned: https://drive.google.com/file/d/157SoRhiVQzsWbSFlaV5N-vzkxKCvTIlf/view?usp=sharing

# Partial Shape Matching Code

Coming soon



