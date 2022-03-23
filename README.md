# portfolio
이 페이지는 제가 진행한 프로젝트들을 소개하는 페이지입니다.

## Table of Contents
- [boiler-plate](#boiler-plate)
- [hello-rest](#hello-rest)

## [boiler-plate](https://github.com/leesh5000/boiler-plate)

`react` `react-redux` `redux-saga` `spring framwork` `jwt`

boiler-plate 는 대부분의 웹 어플리케이션의 기본 기능인 회원가입, 로그인, 로그아웃을 기능을 구현한 프로젝트입니다. 프론트서버는 "리액트를 다루는 기술"의 내용의 참고하였으며 백엔드 서버는 spring framework를 사용하여 구현하였습니다. 유저 인증은 토큰 방식으로 인증됩니다.

### PS

이 프로젝트를 진행하면서 "토큰 인증 방식을 어떻게 구현할까?"에 대해서 고민을 많이 할 수 있었습니다. 가장 기본적으로는 유저 정보가 담긴 하나의 토큰을 발행해서 유저 인증으로 사용하는 것입니다. 하지만, 토큰은 어디까지나 유출의 위험이 있습니다. 따라서, 이에 대한 보완책으로 유저 정보가 담긴 토큰은 만료기간을 짧게하고 이 토큰을 갱신하느 refresh token을 만료기간을 길게하여 안전하 곳에 저장하는 것입니다.


## [hello-rest](https://github.com/leesh5000/hello-rest)

`spring hateoas` `spring rest docs` `tdd`

hello-rest 프로젝트는 진짜 rest 아키텍처를 설계하고 구현해보고자 하는 목적으로 만들었습니다. 여기서 "진짜 rest 아키텍처"란, 로이 필딩이 정의한 rest 아키텍처 가이드 원칙에 따르는 rest api를 말합니다. 대부분의 rest api들이 사실 진정한 rest api 설계 원칙을 지키지 않았습니다. 그 중에서도 특히, self-descriptive와 hateoas가 많이 지켜지지 않는데, 본 프로젝트에서는 api의 응답에 메세지를 해석하 수 있는 문서 링크 정보를 넣음으로써 self-descriptive를 만족시켰고, api 응답에 애플리케이션 상태 전이가 가능한 하이퍼 링크를 추가함으로써 hateoas를 만족시켰습니다.

### PS

추가적으로 본 프로젝트에서는 tdd를 기반으로 진행되었으며, spring rest docs를 사용하여 테스트 통과 후 api 문서 자동화 기능도 구현하였습니다.
