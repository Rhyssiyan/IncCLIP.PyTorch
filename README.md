# Generative Negative Text Replay for Continual Vision-Language Pretraining
Vision-language pre-training (VLP) has attracted increasing attention recently.
With a large amount of image-text pairs, VLP models trained with contrastive loss have achieved impressive performance in various tasks, especially the zero-shot generalization on downstream datasets.
In practical applications, however, massive data are usually collected in a streaming fashion, requiring VLP models to continuously integrate novel knowledge from incoming data.
This work is targeting the continual pretraining of vision-language pretrained model like CLIP. 
We apply contrastive loss and cross-modal knowledge distillation loss for training.
Moreover, we adopt pseudo text replay to augment training.
We incrementally pre-train our model on the both instance and class incremental splits of Conceptual Caption dataset, and evaluate the model on zero-shot image classification and image-text retrieval tasks.
Our method consistently outperforms the existing baselines with a large margin, which demonstrates its superiority.
