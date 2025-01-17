---
title: Cluster
draft: false
tags:
  - devops
  - infra-base
aliases:
  - Cluster
  - 클러스터
---

> [!Info]
> 이 사이트에서 언급하는 [[cluster|클러스터]]는 주로 [[k8s|쿠버네티스]]의 클러스터를 의미한다.

# Definition
- 같은 목적을 위해 연결된 컴퓨팅 도구들의 집합


# Example
- **같은 네트워크에 설치된 10대의 컴퓨터**. 사용자는 한 번의 명령으로 10대의 컴퓨터를 모두 활용할 수 있다.
- **한 컴퓨터 속에 생성된 5개의 가상 머신**. 사용자는 한 번의 명령으로 5개의 가상 머신을 모두 활용할 수 있다.
- **두 컴퓨터에 각각 3개씩 생성된 가상 머신**. 이 때, 모든 가상 머신은 서로 통신할 수 있게 설정되어 있다. 사용자는 한 번의 명령으로 모든 가상 머신을 활용할 수 있다.
- **우리 집 공유기에 설치된 라즈베리 파이, 최근에 산 노트북 그리고 오래된 데스크탑**. 한 번의 명령으로 모든 장비를 사용할 수 있다면 클러스터라 할 수 있다.
- 회사에서 4대의 컴퓨터로 구성된 쿠버네티스. 컴퓨터들이 쿠버네티스라는 하나의 그룹이 되어서 문제 해결을 위한 [[container|컨테이너]]를 실행한다.
