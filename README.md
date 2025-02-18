# DDIM model

## Training
- DDPM 기본 모델과 동일함
- Training 방법도 동일

## Sampling
- DDIM sampling 식에 따라 dt씩 건너뛰며 sampling 진행
- dt 너무 크면 sample 손상됨

## Result (tot 1000 steps)
- dt = 25
- ![image](https://github.com/user-attachments/assets/8072e1d0-e603-4bfb-ad78-e9d420dac69d)
- dt = 100
- ![image](https://github.com/user-attachments/assets/b152bbbc-4f8d-43fa-88a6-858e38a6c6e7)
- dt = 500
- ![image](https://github.com/user-attachments/assets/c1d85ff6-870a-4405-9f8b-d951eea0acc3)
