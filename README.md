# Workspaces

이 워크스페이스는 여러 서브모듈을 포함하는 프로젝트입니다. 각 서브모듈은 별도의 Git 레포지토리로 관리됩니다.

## 서브모듈

- **blogs**: 개인 블로그 사이트 ([gurumee92.github.io](https://github.com/gurumee92/gurumee92.github.io.git))
- **projects/studies**: 학습 자료 및 프로젝트 ([Studies](https://github.com/gurumee92/Studies.git))
- **projects/settings**: 설정 파일 및 환경 설정 ([Settings](https://github.com/gurumee92/Settings.git))

## 설치 및 사용

1. 이 레포지토리를 클론합니다:
   ```bash
   git clone https://github.com/gurumee92/Workspaces.git
   cd Workspaces
   ```

2. 서브모듈을 초기화하고 업데이트합니다:
   ```bash
   git submodule init
   git submodule update
   ```

3. 각 서브모듈의 내용을 확인하려면 해당 폴더로 이동하세요.

## 라이선스

이 프로젝트는 [LICENSE](LICENSE) 파일에 명시된 라이선스에 따라 배포됩니다.