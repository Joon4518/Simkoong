#  심쿵 – 유저 선호 이미지 기반 이성 추천 웹 서비스

> 사용자가 선호하는 이성의 이미지를 선택하면, 얼굴 스타일이 유사한 이성을 추천해주고, 실시간 채팅까지 가능한 AI 기반 매칭 서비스입니다.

---

## 프로젝트 소개

심쿵은 사용자들의 이상형 이미지를 바탕으로 AI를 통해 유사한 이성을 추천하는 웹 서비스입니다.  
VGG16 모델로 얼굴 특징을 추출하고, 코사인 유사도 기반 추천 시스템을 통해 비슷한 외모 스타일의 이성을 매칭합니다.  
추천된 사용자와는 실시간 채팅이 가능하며, 거리 및 조건에 따른 필터링을 통해 현실적인 만남까지 고려했습니다.

---

## 시장 현황 및 필요성

- AI 기반 매칭 서비스에 대한 관심 증가
- 단순 스와이프 방식이 아닌 외형 기반 선호도 추천 니즈 증가
- 기존 소개팅 앱은 텍스트/정보 기반이 주를 이루며, 이미지 분석 기반은 부족
- 거리 및 조건 기반, 이미지 기반, 채팅까지 연결된 통합형 추천 서비스의 필요성

---

## 차별성

- 유저가 직접 선택한 이상형 이미지 기반 추천
- VGG16 + IPCA + K-NN + 코사인 유사도를 통한 유사도 분석
- 거리 및 조건에 따른 필터링으로 현실적인 매칭 제공
- WebSocket 기반의 실시간 채팅 기능 제공

---

## 기술 스택

- Backend: Java, Spring Boot, AWS Keyspaces (Cassandra), Python
- Frontend: HTML/CSS, JavaScript
- AI: VGG16, IPCA, K-NN, Cosine Similarity
---

## 주요 기능 소개
