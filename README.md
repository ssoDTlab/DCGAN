# DCGAN (Deep Convolutional Generative Adversarial Network)

### 🔍 프로젝트 소개
DCGAN(Deep Convolutional Generative Adversarial Network)은 생성적 적대 신경망(GAN)의 한 유형으로, 합성곱 신경망(CNN)을 활용하여 고품질의 이미지를 생성하는 모델입니다. 이 프로젝트에서는 DCGAN을 구현하고, 학습 과정을 기록하며, 생성된 이미지를 시각화합니다.

### 1️⃣ 데이터셋 준비
- 데이터셋: CelebA

### 2️⃣ 모델 아키텍처
- **생성자(Generator)**:
  - 랜덤 노이즈를 입력받아 점진적으로 해상도를 증가시키며 이미지를 생성
  - Transposed Convolution, Batch Normalization, ReLU 사용
- **판별자(Discriminator)**:
  - 입력된 이미지가 실제(real)인지 생성된(fake)인지 구별
  - Convolution, Batch Normalization, LeakyReLU 사용

## CelebA 데이터셋 결과 예시
![Reconstructed](https://github.com/ssoDTlab/VAE/blob/main/result.png)


## 📌 참고 자료
- 논문: [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434)
- PyTorch 공식 튜토리얼
