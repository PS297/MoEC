# MoEC

## Abstarct
Recent studies on explainable machine learning models often analyse feature importance
after training, but this results in a model that does not capture feature dependencies and requires extra
computational resources for explainability. We propose a method for training a supervised learning model
through multi-objective optimisation that considers accuracy and feature importance in a unified framework.
This method provides an explainable training procedure that consistently minimises the model’s loss and
maximises individual feature importance objectives, improving classification decision-making. We explore
interpretable model training using many-objective and bi-objective optimisation formulations. Choosing an
interpretable framework from these pathways is challenging, so we propose outranking them by constructing
a credibility index based on performance metrics. Our experiments on the UCI repository and medical image
datasets show the benefits of capturing feature importance early, ensuring intrinsic explainability.

## Article Citation
@ARTICLE{11363191,
  author={Gupta, Pragya and Mondal, Sanchita and Aishwaryaprajna and Guha, Debashree and Chakraborty, Debjani},
  journal={IEEE Access}, 
  title={Ranking Feature Importance Objectives for Explainable Classification}, 
  year={2026},
  volume={},
  number={},
  pages={1-1},
  keywords={Training;Optimization;Indexes;Computational modeling;Mathematical models;Accuracy;Predictive models;Performance metrics;Feature extraction;Analytical models;Multi-criteria decision making;explainability;feature importance;Shapley value;outranking;classification},
  doi={10.1109/ACCESS.2026.3657343}}


## Dataset Citation
@article{kulyabin2024octdl,
  title={Octdl: Optical coherence tomography dataset for image-based deep learning methods},
  author={Kulyabin, Mikhail and Zhdanov, Aleksei and Nikiforova, Anastasia and Stepichev, Andrey and Kuznetsova, Anna and Ronkin, Mikhail and Borisov, Vasilii and Bogachev, Alexander and Korotkich, Sergey and Constable, Paul A and others},
  journal={Scientific data},
  volume={11},
  number={1},
  pages={365},
  year={2024},
  publisher={Nature Publishing Group UK London}
}
