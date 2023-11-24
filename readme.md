# Next.js App Router Playground

이 프로젝트는 Next.js 라이브러리를 사용한 프론트엔드 웹페이지에서 앱 라우터를 활용한 샘플 페이지들이 구성되어있는 프로젝트를 한글로 번역하고 필자가 보기 쉽게 수정한 레포지토리 입니다.

- 레이아웃: 상태를 보존하고 다시 렌더링을 피하면서 UI를 쉽게 공유할 수 있습니다.
- 서버 컴포넌트: 가장 동적인 애플리케이션을 위해 서버를 기반으로 하는 것이 기본값입니다.
- 스트리밍: 즉시 로딩 상태를 표시하고 업데이트를 스트리밍할 수 있습니다.
- 데이터 가져오기를 위한 서스펜스: async/await 지원 및 컴포넌트 단위에서 데이터 가져오기를 위한 use 훅을 사용할 수 있습니다.

앱 라우터는 기존의 pages 디렉토리와 함께 증분 적용이 가능합니다. Next.js 13으로 업그레이드할 때 앱 라우터를 사용할 필요는 없지만, 더 적은 JavaScript를 배포하면서 복잡한 인터페이스를 구축하기 위한 기반을 마련하고 있습니다.

## Settings

#### Node.js < 18  
현재 Node.js 18 이상 버전에서 `npm run dev` 실행 시  
ERR_OSSL_EVP_UNSUPPORTED 이슈가 있습니다.  
`.nvmrc` 에 기재된 Node.js 버전 사용을 권고합니다.  

1. dependencies 설치:

- 만약 npm을 사용하여 설치 시 시간이 매우 오래 걸릴 수 있습니다.
- [pnpm](https://pnpm.io/) 패키지 매니저를 globally하게 로컬PC에 추가로 설치하고 dependencies를 설치해주세요.

```sh
# pnpm 패키지 매니저 설치
npm install -g pnpm

# pnpm 실행이 안될 시 Powershell에 해당 명령어 권한 주기
Set-ExecutionPolicy RemoteSigned

# 패키지 설치
pnpm install
```

2. 개발 서버 시작하기:

```sh
pnpm dev
```

## 공식문서

https://nextjs.org/docs
