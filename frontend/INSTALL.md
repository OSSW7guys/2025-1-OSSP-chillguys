## 프로젝트 설치 및 실행 방법

이 프로젝트를 실행하기 위해서는 Node.js와 npm (또는 pnpm)이 설치되어 있어야 합니다.

### 1. 의존성 설치

`frontend` 디렉토리로 이동하여 다음 명령어를 실행하여 필요한 모듈들을 설치합니다:

```bash
cd frontend
pnpm install  # 또는 npm install
```

**필요한 모듈 목록:**

*   `@tailwindcss/vite`
*   `axios`
*   `react`
*   `react-dom`
*   `react-router-dom`
*   `tailwindcss`

### 2. 개발 서버 실행

모듈 설치가 완료되면, 다음 명령어를 사용하여 개발 서버를 시작할 수 있습니다:

```bash
pnpm run dev  # 또는 npm run dev
```

### 3. 빌드

배포를 위해 프로젝트를 빌드하려면 다음 명령어를 사용합니다:

```bash
pnpm run build  # 또는 npm run build
``` 