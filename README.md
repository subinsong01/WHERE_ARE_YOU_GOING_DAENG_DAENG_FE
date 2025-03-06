# 🐶 댕댕어디가 - 반려동물 동반 가능 시설 공유 플랫폼
<img width="1438" alt="댕댕어디가" src="https://github.com/user-attachments/assets/e9fa6e63-1ad6-44d0-9232-81a347004747" />

## 🩷 댕댕어디가 플렛폼 소개
<strong>반려동물과 함께 갈 수 있는 장소만 확인할 수는 없을까?🧐</strong><br>
댕댕어디가는 반려동물과 함께 외출할 수 있는 시설 정보를 공유함으로써 , 견주들이 보다 편리하고 쾌적하게 외출을 즐길 수 있도록 돕습니다.<br>
이를 통해 반려동물과 함께하는 활동의 범위가 넓어지고,외출 시의 부담을 줄여주는 서비스를 제공합니다✨.<br>

- 🔗 <a href="https://fronttest.daengdaeng-where.link/"> 서비스 둘러보기 : 댕댕어디가 공식 웹사이트</a>
- 🔗 <a href="https://github.com/WHERE-ARE-YOU-GOING-DAENG-DAENG/WHERE_ARE_YOU_GOING_DAENG_DAENG_FE"> Frontend Repository</a>

## 🩷 프로젝트 기간 
**2024.11.12 ~ 2024.12.19**

## 🩷 리팩토링 기간 
**2025.01.14 ~ 2025.02.17**

**리팩토링 및 최적화 과정** 
<a> : https://devsubin.hashnode.dev/</a>

## 🩷 맡은 페이지 & 역할 
### 프론트엔드(FE)
  - 반려동물 CRUD
  - 유저 마이페이지
  - 리뷰 CRUD
  - How-to-guide 페이지 및 배너 제작
  - 알림(FCM)
  - Admin페이지
  - 스토리 업로드 및 삭제 기능 구현
    
## 🩷 Figma
<a href="https://www.figma.com/design/0cGW8rkHYLpa2Q2tDC7uSY/%EC%82%B0%EC%B1%85%EC%8B%9C%EC%BC%9C%EC%A1%B0?node-id=2142-228&t=TZzNLFFZLisTf3yL-1">**🔗 Figma 확인하기**</a>
<br />
<br />
<img width="1048" alt="figma" src="https://github.com/user-attachments/assets/b3994d96-ecb2-4a4c-9bac-a62b2a482c55" />

## 🩷 프로젝트 폴더 구조

### Frontend
<details>
  <summary><strong> ✨ 확인하기</strong> </summary>

```plaintext
daeng/
├── .storybook            // Storybook 설정 및 파일
├── node_modules          // Node.js 패키지
├── public                // 정적 리소스
│   ├── data/             // 정적 JSON 데이터
│   │   └── sig.json.gz
│   ├── alarm_logo.png    // 알람 로고 이미지
│   ├── favicon.svg       // 파비콘 파일
│   └── firebase-messaging-sw.js  // Firebase 메시징 스크립트
├── src/
  ├── components/      // UI 컴포넌트
  │   └── commons/      // 공통 컴포넌트
  ├── pages/           // 페이지 단위 컴포넌트
  ├── firebase/        // 파이어베이스(FCM)
  ├── hooks/           // 커스텀 훅
  ├── stores/          // Zustand 스토어 파일
  ├── utils/           // 유틸리티 함수
  ├── data/            // 더미데이터
  ├── routes/          // 라우트 관련
  ├── stories/         // 스토리북 파일
  ├── style/           // 스타일 관련 (CSS 등)
  ├── services/        // API 요청 및 데이터 처리
  └── assets/          // 이미지, 폰트 등 정적 리소스
      └── icons/       // icon 파일
```
<br />
</details>

## 🩷 유저 및 피드백

### 📅 12월 10일에 1차 MVP 완성
- 이후 **구글 광고 및 카페 홍보글 작성(강사모)** 진행 
- **네이버 애널리틱스**로 유저 및 유입 경로 분석

  

## 🩷 기술 스택
<h3>FrontEnd</h3>

<table>
  <tr>
    <td><img width="100" src="https://camo.githubusercontent.com/5206020f736992bcb8c69db0378b675c6a0bc868c1d7d7bcb6605bfbbde8ad2b/68747470733a2f2f70726f66696c696e61746f722e7269736861762e6465762f736b696c6c732d6173736574732f68746d6c352d6f726967696e616c2d776f72646d61726b2e737667" alt="html"></td>
    <td><img width="100" src="https://images-ext-1.discordapp.net/external/jvLCZImVaQOR4o5hqrq8J7gVR-J4hwg8SJSwA0jenLQ/https/noticon-static.tammolo.com/dgggcrkxq/image/upload/v1710061458/noticon/wcbbvx44ppavzhuptuwd.png?format=webp&quality=lossless&width=400&height=400" alt="styled-component"></td>
    <td><img width="100" src="https://camo.githubusercontent.com/65e0cf3127cd71af7cf9e4da84a7370bbd445bb949ba9fbb06ee0d3dc7a634fb/68747470733a2f2f70726f66696c696e61746f722e7269736861762e6465762f736b696c6c732d6173736574732f6a6176617363726970742d6f726967696e616c2e737667" alt="js"></td>
    <td><img width="100" src="https://images-ext-1.discordapp.net/external/KBcTLO8mxeMn4SFQ_WBE3UJ7cOvUHvzmGkTHn08BZM8/https/noticon-static.tammolo.com/dgggcrkxq/image/upload/v1679535484/noticon/arqfoi6i7gubuqkpigud.png?format=webp&quality=lossless&width=400&height=400" alt="vite"></td>
    <td><img width="100" src="https://camo.githubusercontent.com/cc4e0bd91b89404a61e0f207ea47434aeb615edec6d4f6bcb7523680d64ea06b/68747470733a2f2f70726f66696c696e61746f722e7269736861762e6465762f736b696c6c732d6173736574732f72656163742d6f726967696e616c2d776f72646d61726b2e737667" alt="react"></td>
  </tr>
  <tr>
    <th>HTML</th>
    <th>Styled</th>
    <th>JS</th>
    <th>Vite</th>
    <th>React</th>
  </tr>
  </table>
  <table>
   <tr>
    <td><img width="100" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1712215318/noticon/t0boj5btqesxnyxp4nfq.png" alt="gsap"></td>
    <td><img width="100" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1566913958/noticon/uoqjdixts4lwsgtsa1pd.png" alt="firebase"></td>
    <td><img width="100" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1675253316/noticon/gg2mfsvpu2aje4f8rpuc.png" alt="zustand"></td>
    <td><img width="100" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1716180510/noticon/seh9elkswcqbrpsxvmhd.png" alt="axios"></td>
    <td><img width="100" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1566952480/noticon/fyec5eye4l6hyxlpfxze.png" alt="storybook"></td>
  </tr>
  <tr>
    <th>Gsap</th>
    <th>Firebase</th>
    <th>Zustand</th>
    <th>Axios</th>
    <th>Storybook</th>
  </tr>
</table>



<h3>Communication</h3>
<table>
  <tr>
    <td><img width="100" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1566899596/noticon/slhw4nu8hybreryigopq.png" alt="gitbug" /></td>
    <td><img width="100" src="https://images-ext-1.discordapp.net/external/xW2pjW1THv1Zdzo_NWk1EuIoL5j7hWHVK9LvG7pD_AA/https/noticon-static.tammolo.com/dgggcrkxq/image/upload/v1640152045/noticon/albswwsjaaxvxbyhmwig.png?format=webp&quality=lossless&width=400&height=400" alt="discord"></td>
    <td><img width="100" src="https://images-ext-1.discordapp.net/external/azXealsvy6EBai5UV6z3mP0QOVcwPnKAxH5o7jhRs8Y/https/noticon-static.tammolo.com/dgggcrkxq/image/upload/v1608448196/noticon/a0fgk99dgqtyrwwmqsbt.png?format=webp&quality=lossless&width=400&height=400" alt="figma"></td>
    <td><img width="100" src="https://images-ext-1.discordapp.net/external/HmQy4lniRwIGodKeYCEnxF1dM_bLyuYJ41ju7zIQ6Mc/https/noticon-static.tammolo.com/dgggcrkxq/image/upload/v1633514562/noticon/jodwxqluutquo62s82de.png?format=webp&quality=lossless&width=400&height=400" alt="notion"></td>
    <td><img width="100" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1566914615/noticon/pogcyufuizgdsl9m5u2w.jpg" alt="Jira"></td>
    <td><img width="100" src="https://noticon-static.tammolo.com/dgggcrkxq/image/upload/v1566912512/noticon/jqqvnjhzhdwptlnp96p5.png" alt="google sheet"></td>
      </tr>
        <tr>
          <th>Github</th>
          <th>Discord </th>
          <th>Figma</th>
          <th>Notion</th>
          <th>Jira </th>
          <th>Google sheet</th>
        </tr>
  </table>

## 🩷 Git convention

### Frontend
<details>
  <summary><strong> ✨ 확인하기</strong> </summary>


<br />

```
이모지 = :코드:
```

| 타입         | 이모지 | 코드             | 설명                                                           | 예시                                                  |
| ------------ | ------ | ---------------- | -------------------------------------------------------------- | ----------------------------------------------------- |
| **feat**     | ✨     | sparkles         | 새로운 기능을 추가할 때 사용합니다.                            | `✨ feat: 로그인 폼 유효성 검사 추가`                 |
| **fix**      | 🐛     | bug              | 버그를 수정할 때 사용합니다.                                   | `🐛 fix: 로그인 버그 수정`                            |
| **style**    | 💄     | lipstick         | 사용자 인터페이스 관련 변경 사항.                              | `💄 style: 네비게이션 바 디자인 수정`                 |
| **refactor** | 🎨     | art              | 버그 수정이나 기능 추가 없이 코드 구조를 개선할 때 사용합니다. | `🎨 refactor: 컴포넌트 상태 관리 로직 단순화`         |
| **perf**     | ⚡     | zap              | 성능을 개선하는 코드 변경.                                     | `⚡️ perf: 이미지 로딩 시간 최적화`                   |
| **test**     | ✅     | white_check_mark | 테스트 코드를 추가하거나 수정할 때 사용합니다.                 | `✅ test: 버튼 컴포넌트에 대한 단위 테스트 추가`      |
| **docs**     | 📝     | memo             | 문서만 변경할 때 사용합니다.                                   | `📝 docs: 설치 단계 README에 추가`                    |
| **chore**    | 🔧     | wrench           | 소스나 테스트 파일을 수정하지 않는 일반적인 작업이나 업데이트. | `🔧 chore: 종속성 패키지 업데이트`                    |
| **revert**   | ⏪     | rewind           | 이전 커밋을 되돌릴 때 사용합니다.                              | `⏪ revert: "로그인 폼 유효성 검사 추가" 커밋 되돌림` |
| **init**     | 🎉     | tada             | 프로젝트 초기 설정 시 사용합니다.                              | `🎉 init: React 프로젝트 초기 설정`                   |
| **delete**   | 🔥     | fire             | 코드/파일 삭제.                                                | `🔥 delete: 안 쓰는 로그인 컴포넌트 삭제`             |
| **wip**      | 🚧     | construction     | 작업 중이거나 실험적인 변경 사항.                              | `🚧 wip: 새로운 인증 방법을 실험 중`                  |


## 결과
<img width="1000" alt="프론트엔드 깃 컨벤션" src="https://github.com/user-attachments/assets/188806f9-9c6f-48d8-bb7b-ec59426e0292" />

<br />
</details>
