Code and Model Access
This project is organized into multiple Jupyter notebooks, each targeting a specific dataset and experimental setup:

Alzheimers_v3.ipynb: Implements and evaluates models on the OASIS dataset, including baseline CNN, Stacked CNN, and ResNet50.

Alzheimers_v5.ipynb: Focuses on the ADNI dataset, applying the same set of architectures with additional data augmentation and preprocessing strategies.

The trained models and associated checkpoints are hosted on Hugging Face and can be accessed via the following repositories:

OASIS Models and Checkpoints:
git clone https://huggingface.co/RajathRajesh12/Alzheimers1

ADNI Models with Augmentation:
git clone https://huggingface.co/RajathRajesh12/AlzheimersADNIAug

These repositories contain serialized model weights, training configurations, and logs that enable reproducibility and further experimentation.

