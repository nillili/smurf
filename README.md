🍄 스머프 멀티 술래잡기 (Smurf Catch Game)

이 프로젝트는 HTML5 Canvas와 Firebase를 활용하여 만든 실시간 웹 멀티플레이어 게임입니다.
복잡한 서버 구축 없이 Firebase Firestore를 통해 플레이어 간의 위치와 상호작용을 실시간으로 동기화합니다.

🎮 게임 설명

인원: 5인 ~ 10인 (방장을 포함하여 멀티플레이 가능)

역할:

🧙‍♂️ 가가멜 (술래): 일반 스머프들을 쫓아가서 모두 아웃시키면 승리합니다.

🐈 아즈라엘: 손을 잡고 무적이 된 스머프들을 방해하여 손을 떼어놓습니다.

🎅 파파스머프: 가가멜에게 잡힌 스머프들을 10초 뒤에 구출할 수 있습니다.

🧢 스머프 (시민): 가가멜을 피해 1분 동안 살아남거나, 서로 손을 잡아 무적 상태가 될 수 있습니다.

🚀 기술 스택

Frontend: HTML5 Canvas, Vanilla JavaScript, Tailwind CSS (CDN)

Backend / BaaS: Firebase (Authentication 익명 로그인, Cloud Firestore 실시간 동기화)

⚙️ 실행 방법

이 프로젝트는 별도의 Node.js 서버나 빌드 과정이 필요 없는 순수 HTML 파일입니다.

이 저장소(Repository)를 클론(Clone) 하거나 다운로드합니다.

Firebase Console에서 프로젝트를 생성하고, Firestore 및 Authentication(익명 로그인)을 활성화합니다.

발급받은 Firebase 설정(Config) 값을 index.html 파일 내부의 firebaseConfig 객체에 덮어씁니다.

index.html 파일을 브라우저(Chrome 등)에서 직접 열어 실행합니다. (file://.../index.html)

📌 주의사항

Firebase 보안 규칙(Firestore Rules)은 반드시 테스트 모드(읽기/쓰기 허용) 또는 본 앱 구조에 맞게 설정해야 데이터가 실시간으로 동기화됩니다.
