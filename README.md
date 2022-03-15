# portfolio
이 페이지는 제가 진행한 프로젝트들을 소개하는 페이지입니다.


## Table of Contents
- [boiler-plate](#boiler-plate)
- [hello-rest](#hello-rest)

## [boiler-plate](https://github.com/leesh5000/boiler-plate)

boiler-plate 는 대부분의 웹 어플리케이션의 기본 기능인 회원가입, 로그인, 로그아웃을 기능을 구현한 프로젝트입니다. 프론트서버는 "리액트를 다루는 기술"의 내용의 참고하였으며 백엔드 서버는 spring framework를 사용하여 구현하였습니다. 유저 인증은 토큰 방식으로 인증됩니다.

## [hello-rest](https://github.com/leesh5000/hello-rest)

hello-rest 프로젝트는 진짜 rest 아키텍처를 설계하고 구현해보고자 하는 목적으로 만들었습니다. 여기서 "진짜 rest 아키텍처"란, 로이 필딩이 정의한 rest 아키텍처 원칙을 모두 지키는 rest api를 말합니다. 대부분의 rest api들이 사실 진정한 rest api 설계 원칙을 지키지 않았습니다. 그 중에서도 특히, self-descriptive와 hateoas가 많이 지켜지지 않는데, 본 프로젝트에서는 api의 응답에 메세지를 해석하 수 있는 문서 링크 정보를 넣음으로써 self-descriptive를 만족시켰고, api 응답에 애플리케이션 상태 전이가 가능한 하이퍼 링크를 추가함으로써 hateoas를 만족시켰습니다.
