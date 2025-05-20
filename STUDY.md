# donggle-potal

## 학습 기록

## 2025-05-20

### Node.js 프로젝트 초기화 및 패키지 설치

- Node.js 프로젝트 초기화 및 Express, CORS 설치  
- CORS는 React와 Node.js 간 API 요청 시 발생하는 보안 문제 해결을 위해 사용함  
- 윈도우 PowerShell 실행 정책 문제로 npm 실행 오류 발생 →  
  `Set-ExecutionPolicy RemoteSigned` 명령어로 해결  

### 서버 기본 구조 (`index.js`)

- **express**: Node.js용 웹 프레임워크로, 서버 구축에 사용  
- **cors**: Cross-Origin Resource Sharing 설정을 도와줌 (React와 백엔드 간 요청 문제 해결)  
- `app.use(cors())`: 모든 도메인에서 오는 요청 허용 (개발 단계에서 편리함)  
- `app.use(express.json())`: JSON 형태의 요청 본문(body)을 파싱해서 사용 가능하게 함  
- 기본 GET `/` 라우트: 서버 작동 테스트용, 접속 시 간단한 문자열 응답  
- `app.listen(PORT)`: 지정한 포트에서 서버 실행 및 대기  



 


