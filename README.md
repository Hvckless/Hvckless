# 대표 프로젝트

## 🎬 [Filmelier](https://github.com/Hvckless/filmelier) - 영화 추천 시스템
2,460개 영화 리뷰 데이터 기반 유사 컨텐츠 추천 서비스

- FastText로 영화 리뷰를 임베딩해 142개의 특징점에 대한 유사도를 추출
- 특징점에 대한 영화의 유사도를 계산하는 과정에서 병목이 발생 (한 번 추천에 14분 소요) -> 데이터를 행렬으로 보고 CuPy로 최적화 구현 시도 -> 일반적인 서버 인스턴스는 GPU가 없으므로 NumPy의 Vectorization으로 행렬 연산을 CPU로 병렬 처리 -> 연산 시간을 최종적으로 0.01초로 단축 (약 84,000배 개선)
- 여러 사유로 팀원이 이탈한 이후에도 단독으로 프로젝트 완성

`TypeScript` `Node.JS` `Python` `NumPy` `FastText` `MariaDB`

## Skills
**Main** - JavaScript, TypeScript / Node.JS

**Available** - Python, Java, C++

**Tool** - NumPy, FastText, Git, Docker, VENV, Windows Subsystem for Linux

## Contact

📧 jinhojun00@naver.com
