### Hi there 👋
![image](https://github.com/younkyungkim/NEW-Keyword-Tool/assets/141793731/92d00538-2550-466e-9c1e-8389b12378d8)
**요약**

- 효율적으로 회의를 진행할 수 있도록 도와주는 회의 보조 시스템입니다.

**역할**

- aivle school 빅프로제트 팀원 총 6명이 함께 진행 (AI개발 2명, 프론트엔드 2명, 백엔드 2명)
- AI개발 담당

**주서비스**

- 회의 내용 실시간 인식
- 회의 내용에서 키워드 추출
- 키워드 기반 뉴스 제시 및 요약
- 전체 회의 내용 기반 회의록 작성

**AI 개발**

- 회의 내용  실시간 인식

      - 구글 STT를 이용하여 회의 내용을 실시간으로 인식

- 회의 내용에서 키워드 추출

      - 실시간으로 인식된 회의 내용에서 핵심 단어 추출 (1분 간격으로 키워드 2개)

      - gpt AI를 사용하여 다수의 키워드 추출 → 각 키워드의 가중치를 구하여 상위 2개의 키워드 추출

- 키워드 기반 뉴스 제시 및 요약

      - 핵심 단어를 기반으로 관련성이 높은 뉴스를 크롤링 후 제시하며, 뉴스 내용 요약(gpt-3.5-turbo)

- 전체 회의 내용 기반 회의록 작성

      - 실시간으로 인식한 회의 내용 전체를 회의록 포맷에 맞춰 회의로 작성(gpt-3.5-turbo)

시연영상 아래 이미지 클릭
[![NEW-KT 웹서비스 시연 영상](https://img.youtube.com/vi/S60u_tlDg_I/0.jpg)](https://youtu.be/S60u_tlDg_I)

<!--
**younkyungkim/younkyungkim** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
