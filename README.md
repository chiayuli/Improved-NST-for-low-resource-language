# Improved-NST-for-low-resource-language
Paper title: Improving noisy student training for low-resource languages in End-to-End ASR using CycleGAN and inter-domain losses
This work has been submitted to SIGUL 2024 and is available on arXiv (update link later)

# Abstract
Training a semi-supervised end-to-end speech recognition system using noisy student training has significantly improved performance. However, this approach requires a substantial amount of paired speech-text and unlabeled speech, which is costly for low-resource languages. Therefore, this paper considers a more extreme case of semi-supervised end-to-end automatic speech recognition where there are limited paired speech-text, unlabeled speech (less than five hours), and abundant external text. Firstly, we observe improved performance by training the model using our previous work on semi-supervised learning "CycleGAN and inter-domain losses" solely with external text. Secondly, we enhance "CycleGAN and inter-domain losses" by incorporating automatic hyperparameter tuning, calling "enhanced CycleGAN inter-domain losses." Thirdly, we integrate it into the noisy student training approach pipeline for low-resource scenarios. Our experimental results, conducted on six non-English languages from Voxforge and Common Voice, show a 20% word error rate reduction compared to the baseline teacher model and a 10% word error rate reduction compared to the baseline best student model, highlighting the significant improvements achieved through our proposed method. 
# Keywords
speech recognition, low resource, semi-supervised training, CycleGAN, noisy student training

# Experiment setup and dataset
1) download common voice dataset 
2) download Leipzig text corpora
3) copy changes and recipie to the corresponding espnet directory


