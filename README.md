# 💊 경구약제 객체 탐지 프로젝트  
> **사진 속 최대 4개의 알약을 인식하고, 이름과 위치를 탐지하는 딥러닝 기반 객체 검출 프로젝트**


## ✓ 프로젝트 기간  
**2025.05.22 ~ 2025.06.10**


## ✓ 프로젝트 개요  
경구약제를 대상으로 **YOLO 기반 객체 탐지 모델**을 구현하고,  
**ResNet 분류 모델**을 통해 알약 이름(제품명)을 예측합니다.  
이미지 내 최대 4개의 알약을 대상으로 **클래스와 바운딩 박스 좌표**를 검출하며,  
**Crop → 메타데이터 생성 → 분류**의 전체 파이프라인을 구성했습니다.


## ✓ 기술 스택
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) 


## ✓ 프로젝트 아키텍처
![YOLO_Resnet](https://github.com/user-attachments/assets/68e9f9ae-bea5-4a57-a488-06a5910c2060)


## ✓ 주요 기능  
-  **YOLO 기반 객체 탐지**  
  - 알약 위치를 정확히 바운딩 박스로 검출  
- **Crop 및 메타데이터 생성**  
  - 검출된 알약 영역만 추출해 별도 데이터로 저장  
- **ResNet 기반 분류 모델**  
  - 알약 이미지를 바탕으로 제품명(class) 분류  


## ✓ 실험 과정 및 결과
![process_result](https://github.com/user-attachments/assets/924b6d25-4209-402b-9c19-0b3da1617b88)


## ✓ 프로젝트 정리 및 회고
🔗 [정리 및 회고 블로그](https://j-linux-journal.tistory.com/category/%F0%9F%93%97%20%ED%86%A0%EC%9D%B4%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8/%F0%9F%92%8A%20%EA%B2%BD%EA%B5%AC%EC%95%BD%EC%A0%9C%20%EC%9D%B4%EB%AF%B8%EC%A7%80%20%EA%B0%9D%EC%B2%B4%20%EA%B2%80%EC%B6%9C%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)

