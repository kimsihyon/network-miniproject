# network-miniproject
# 내부 네트워크 설계 및 구성 미니 프로젝트

본 문서는 CCCR 오픈소스 기반 클라우드 플랫폼(PaaS) 엔지니어 부트캠프 과정 중 수행한 미니 프로젝트 결과물입니다. IPv4 서브넷팅 및 정적 라우팅을 활용하여 내부 네트워크를 설계하고, 실습을 통해 구성한 내용을 정리하였습니다.

—

## 📌 프로젝트 개요

- **프로젝트명**: 내부 네트워크 설계 및 구성
- **작성자**: 김시현
- **일자**: 2025.03.20
- **이메일**: kimsh-1128@naver.com

—

## 🎯 프로젝트 목적

- IPv4 서브넷팅을 통한 네트워크 분할 구성
- 정적 라우팅(Static Routing) 기반 네트워크 연결
- 기본적인 네트워크 장비 구성 및 통신 확인 실습

—

## 🗺️ 네트워크 설계 개요

- 총 4대의 라우터, 4대의 스위치, 4대의 PC 구성
- 라우터 간 연결은 Cross Over Cable 사용
- 서브넷 마스크를 이용한 7개의 네트워크로 분할
![Image](https://github.com/user-attachments/assets/705a5c9c-d2ea-4504-8d52-6febdfbc94eb)
—

## 🧩 서브넷 설계

![Image](https://github.com/user-attachments/assets/1db42adc-8647-4111-a3c9-fab7b75cf810)


### 라우터 간 연결용 네트워크

![Image](https://github.com/user-attachments/assets/99f06cf3-6376-4a6c-af23-95b795c87ce2)


—

## ⚙️ 장비 및 IP 구성

### PC 설정

![Image](https://github.com/user-attachments/assets/fe8f3bc5-8721-459b-957e-bb4f3117f43c)


### 라우팅 테이블


![스크린샷 2025-03-25 172402](https://github.com/user-attachments/assets/d91726ac-7d3e-4699-bca2-726c6b6f9941)

—

## 🧭 라우팅 및 통신 확인

- 각 라우터에 정적 라우팅 설정

![스크린샷 2025-03-25 172258](https://github.com/user-attachments/assets/2a344b3f-d685-4e17-a484-131ee1c73ac3)
![스크린샷 2025-03-25 172224](https://github.com/user-attachments/assets/ba39c9db-b7a7-4f97-8600-22cfb781cea1)
![스크린샷 2025-03-25 172147](https://github.com/user-attachments/assets/9a41f526-ffa5-4b42-8e56-fa192a48aaf6)
![스크린샷 2025-03-25 172102](https://github.com/user-attachments/assets/e10eae2b-f917-49a6-8fd4-ecdd1228a18a)

  
- ping 테스트를 통해 PC 간 통신 확인
  
![스크린샷 2025-03-25 172932](https://github.com/user-attachments/assets/7f359d06-8fed-45c4-83dc-cee88cd55ca4)
![스크린샷 2025-03-25 172857](https://github.com/user-attachments/assets/56caa21a-0060-48b7-8f3b-f181d6ccf2b7)
![스크린샷 2025-03-25 172821](https://github.com/user-attachments/assets/fdfb2873-b4b5-41b2-a087-a4dd1d8ab3b3)
![스크린샷 2025-03-25 172734](https://github.com/user-attachments/assets/75c073b3-41a7-4ba7-90c4-d66376d43309)
![스크린샷 2025-03-25 172651](https://github.com/user-attachments/assets/3a3c8136-d8d4-4640-964e-4ff335b589b1)
![스크린샷 2025-03-25 172616](https://github.com/user-attachments/assets/d1afd28c-3b75-49b6-85ac-5fa85c48ff5c)

—

## 🔒 향후 개선점

1. **동적 라우팅 적용**
   - OSPF, EIGRP와 같은 프로토콜 도입을 통해 확장성과 유지보수성 향상
2. **보안 강화**
   - ACL 적용, 패킷 필터링, 방화벽 도입
   - VLAN을 통한 네트워크 분리

—

## ✅ 프로젝트 결과 요약

- IPv4 서브넷팅 및 정적 라우팅 개념 실습 완료
- 장비 설정을 통해 네트워크 간 통신 검증
- 실무 네트워크 설계 기반 지식 습득

