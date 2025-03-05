# Generative Adversarial Network (GAN) Study


## 📌 Introduction
Generative Adversarial Network (GAN)은 생성 모델 중 하나로, 두 개의 신경망(Generator와 Discriminator)이 경쟁하면서 점점 더 정교한 데이터를 생성하도록 학습하는 모델입니다.

이 저장소는 GAN에 대한 이론적 개념과 실습 내용을 정리하고, Google Colab에서 실험한 Jupyter Notebook 파일을 포함하고 있습니다.

## 🏗 Theory & Concepts
1. **GAN의 기본 개념**
   - GAN은 Goodfellow et al. (2014)에 의해 제안된 생성 모델로, Generator(생성자)와 Discriminator(판별자)가 서로 경쟁하면서 발전함.
   - Generator: 랜덤 노이즈로부터 데이터를 생성
   - Discriminator: 실제 데이터와 생성된 데이터를 구별
   - 두 네트워크는 서로의 성능을 향상시키면서 점점 더 현실적인 데이터를 생성하도록 학습됨.

2. **Loss Function**
   - Generator Loss: 생성된 데이터가 진짜처럼 보이도록 유도
   - Discriminator Loss: 실제 데이터와 생성된 데이터를 정확히 구별하도록 유도
   - 학습이 안정적으로 이루어지도록 다양한 기법이 활용됨 (예: Wasserstein Loss, Gradient Penalty 등)

3. **GAN Variants**
   - DCGAN: CNN을 이용한 GAN 구조
   - WGAN: Wasserstein Loss를 이용한 안정적인 학습
   - CycleGAN: 이미지 스타일 변환을 위한 GAN
   - StyleGAN: 고해상도 이미지 생성을 위한 GAN


## 🏆 Results
### ✅ MNIST 데이터셋 결과 예시
| Random Noise | Generated Image |
|---|---|
| ![Random Noise](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png) | ![Generated Image](https://your-github-url.com/path-to-your-image.png) |

## 🔗 References
- [Goodfellow et al., 2014 - Generative Adversarial Networks](https://arxiv.org/abs/1406.2661)
- [TensorFlow GAN Tutorial](https://www.tensorflow.org/tutorials/generative/dcgan)
- [PyTorch GAN Example](https://github.com/pytorch/examples/tree/main/dcgan)

## 📜 License
MIT License
