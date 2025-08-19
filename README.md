# Oral Cancer Classification Using Few-Shot Learning with CNN and Siamese Networks

## Abstract

This research introduces a comprehensive technique for categorising oral cancer images using deep learning algorithms. The dataset includes a standardized series of grayscale oral cancer images that undergo preprocessing steps, including normalisation, augmentation, and resizing to 299×299 pixels to ensure the model's accuracy and robustness. The pretrained Xception model is primarily based on ImageNet, fine-tuned with the aid of extra dense layers specific to oral cancer classification. Extensive hyperparameter tuning complements the model's performance and achieves high classification accuracy. Additionally, the Siamese network evaluates image pairs and determines their similarity. Performance indicators such as precision, recall, and F1 score were used to validate the model. This highlights the robustness of the model. The dual-model architecture provides a collaborative framework that improves classification accuracy and enhances clinical interpretability through similarity analysis. The proposed approach represents a significant advancement in oral cancer detection and lays the foundation for reliable and scalable diagnostic tools in clinical practice.

## Features

- **Dual-Model Architecture**: Combines Xception CNN and Siamese Networks for enhanced classification
- **Image Preprocessing**: Standardized pipeline with normalization, augmentation, and 299×299 pixel resizing
- **Transfer Learning**: Fine-tuned Xception model pretrained on ImageNet
- **Similarity Analysis**: Siamese network for image pair comparison and similarity evaluation
- **Performance Validation**: Comprehensive evaluation using precision, recall, and F1 score metrics

## Repository Contents

- [`Oral_Cancer_Detection_And_Classification.ipynb`](Oral_Cancer_Detection_And_Classification.ipynb) - Main implementation notebook
- [`README.md`](README.md) - Project documentation
- [`LICENSE`](LICENSE) - License information

## Keywords

Oral Cancer, Deep Learning, Image Classification, Xception Model, Convolutional Neural Networks (CNN), Siamese Networks, Few-Shot Learning, Transfer Learning

## Citation

```bibtex
@INPROCEEDINGS{10958513,
  author={Rajan, Anagha and Oviya, I R},
  booktitle={2024 IEEE 21st India Council International Conference (INDICON)}, 
  title={Oral Cancer Classification Using Few-Shot Learning with CNN and Siamese Networks}, 
  year={2024},
  volume={},
  number={},
  pages={1-6},
  keywords={Adaptation models;Accuracy;Transfer learning;Robustness;Real-time systems;Planning;Convolutional neural networks;Tuning;Cancer;Residual neural networks;Oral Cancer;Deep Learning;Image Classification;Xception Model;Convolutional Neural Networks (CNN);Siamese Networks},
  doi={10.1109/INDICON63790.2024.10958513}}

```

## Authors

- **A. Rajan** - Research and Development
- **I. R. Oviya** - Research and Development

## Contributors
- **Rudraksh Mohanty** - Implementation and Coding

## License

This project is licensed under the terms specified in the [`LICENSE`](LICENSE) file.
