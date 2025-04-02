# 🐶 댕댕어디가 - 반려동물 동반 가능 시설 공유 플랫폼
<img width="1438" alt="댕댕어디가" src="https://github.com/user-attachments/assets/e9fa6e63-1ad6-44d0-9232-81a347004747" />

## 🩷 댕댕어디가 플렛폼 소개
<strong>반려동물과 함께 갈 수 있는 장소만 확인할 수는 없을까?🧐</strong><br>
댕댕어디가는 반려동물과 함께 외출할 수 있는 시설 정보를 공유함으로써 , 견주들이 보다 편리하고 쾌적하게 외출을 즐길 수 있도록 돕습니다.<br>
이를 통해 반려동물과 함께하는 활동의 범위가 넓어지고,외출 시의 부담을 줄여주는 서비스를 제공합니다✨.<br>

- 🔗 <a href="https://fronttest.daengdaeng-where.link/"> 서비스 둘러보기 : 댕댕어디가 공식 웹사이트</a>
- 🔗 <a href="https://github.com/WHERE-ARE-YOU-GOING-DAENG-DAENG/WHERE_ARE_YOU_GOING_DAENG_DAENG_FE"> Frontend Repository</a>

## 🩷 프로젝트 기간 
**2024.11.12 ~ 2024.12.19** <br />
**2025.01.14 ~ 2025.02.17 [리팩토링 진행]**

**최적화 과정을 기록했습니다.**
➡️ <a> https://devsubin.hashnode.dev/</a>
    
## 🩷 Figma
<br />
<img width="800" alt="figma" src="https://github.com/user-attachments/assets/b3994d96-ecb2-4a4c-9bac-a62b2a482c55" />

## 🩷 맡은 페이지 & 역할 
### 프론트엔드(FE)
🙌🏻 `반려동물 CRUD`
<details>
  <summary><strong>✨ 클릭 </strong></summary>
  <img src="https://github.com/user-attachments/assets/dd58b9b6-1008-4239-8a76-2186e102ed46" alt="pet_add">

    1. 반려동물 이미지를 등록할 때 Presigned URL을 활용하여 직접 파일을 업로드하여 성능을 최적화하고 서버 부하를 줄였습니다.
    2. 반려동물 이미지 등록, 수정, 추가 기능에서 이미지 등록 코드 중복을 최소화하기 위해 로직을 util 폴더로 분리하였습니다.
</details>


🙌🏻 `유저 마이페이지`
<details>
  <summary><strong> ✨ 클릭</strong></summary>
  <img src="https://github.com/user-attachments/assets/f887f35d-b4bc-4bc4-ac51-8eb5be25b0ec" alt="pet_add">

    1. skeleton ui를 삽입함으로써 사용자 경험을 향상시켰습니다.
    2. 반려동물의 성별에 따라 아이콘을 다르게 표시하여 직관성을 높였습니다.

</details>

🙌🏻 `알림(FCM)`

<details>
  <summary><strong>✨ 클릭</strong></summary>
  <img src="https://github.com/user-attachments/assets/001f8e71-8121-46f0-a9e7-14fc5b71372b" alt="alarm"> <br />
  <img width="300" src="https://github.com/user-attachments/assets/f3541c05-efc7-42bc-9b24-4c6873c90b8f" alt="alarm">

    1. FCM을 활용한 실시간 알림 기능을 구현하여 사용자 경험을 개선하였습니다.
    2. 백그라운드 및 포그라운드 상태에서도 알림을 받을 수 있도록 설정하였습니다.
    3. 알림 페이지 진입 시 서비스 워커가 자동으로 등록되도록 구현하였습니다.
    4. skeleton ui를 삽입함으로써 사용자 경험을 향상시켰습니다.
</details>

🙌🏻 `리뷰 등록 & 리뷰 조회`

<details>
  <summary><strong>✨ 클릭</strong></summary>
  <img src="https://github.com/user-attachments/assets/103af025-0848-434d-94cb-46a26eb8ba33" alt="리뷰조회">

    1. 게시물 등록 시 이미지와 동영상 첨부를 위해 Presigned URL을 활용하여 성능을 최적화하고 서버 부하를 줄였습니다.
    2. LCP가 큰 아이콘을 useMemo로 최적화하여 렌더링 성능을 개선했습니다.
    3. input 및 select 요소에 aria-label을 추가하여 접근성과 SEO를 향상시켰습니다.
</details>

🙌🏻 `스토리 업로드 및 삭제 기능 구현`

<details>
  <summary><strong>✨ 클릭</strong></summary>
  <img src="https://github.com/user-attachments/assets/3398e61a-9bb1-4a4c-b5cc-e772c31b0f77" alt="story">
</details>
