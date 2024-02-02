# GitHub Actions
CI/CD 도구.

### CI/CD: Continuous Integration / Continuous Deployment
- CI는 빌드 및 테스트 자동화
- CD는 배포 자동화

## 구성 요소
- Event: push/pull request/commit 등
- Workflow: 이벤트가 생기면 수행함
- Job: workflow안에 있음. 병렬 실행 가능, 유닛 테스트 등
  - Step 이용해서 명령어 수행
- Actions: 깃허브 명령어 사용(체크아웃, 셋업 등)
- Runners: 컨테이너, VM이나 Docker등
