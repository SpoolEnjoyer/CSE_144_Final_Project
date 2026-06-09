![alt text](image.png)
Head K-Fold Weights
https://drive.google.com/file/d/1boKoVLqtudlS-i98JsspFvqmHhMtGdhF/view?usp=sharing

Reproducibility 
1. Random seeds and determinism settings. 
Seed = 42
2. Package versions / environment setup steps. 
torch            2.11.0+cu128
torchvision      0.26.0+cu128
transformers     5.9.0
timm             1.0.27
scikit-learn     1.9.0
numpy            2.4.4
pandas           3.0.3
matplotlib       3.10.9
tqdm             4.67.3
pillow           12.2.0
huggingface-hub  1.17.0
safetensors      0.7.0
tokenizers       0.22.2
scipy            1.17.1
python           3.14.0

Request access to DinoV3 on huggingface (takes like 15min-30min to get access)
Insert huggingface token in designated section
Setup Training and test pathways.

3. Exact commands to train and to generate submission.csv. 2
After downloading required packages, inserting the hugging face token and setting up training and test paths. Run All.
 
To run inference, requires backbone loaded so just run all pretty much.

8 Team Contributions 
1. Member 1: Robert Schmidling: model selection, training setup, model evaluation
2. Member 2: William: parameter tuning, testing, model configuration
3. Member 3: Leo: Directory configuration, data preprocessing, data augmentation, data embedding
9 References 
1. TorchVision documentation / pretrained model sources. 
Pretrained model - https://huggingface.co/facebook/dinov3-vitl16-pretrain-lvd1689m
DinoV3 License - https://ai.meta.com/resources/models-and-libraries/dinov3-license/

2. Any papers or tutorials used
DinoV3 - https://arxiv.org/abs/2508.10104
