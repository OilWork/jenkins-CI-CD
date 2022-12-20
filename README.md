# jenkins-CI-CD

## goal : jenkins를 통해 CI/CD 파이프 라인 구축

### flow
- 코드 수정
- dev branch에 커밋될시에 git hook을 통해 jenkins에서 git clone 실시
  - jenkins에서 build실시하여 CI test 실시
- main branch에 커밋될시에 git hook을 통해 jenkins에서 git clone 실시
  - jenkins에서 build 후에 클라우드에 배포 및 재시작
