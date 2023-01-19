# NestJS 모듈
- @Module 주석달린 클래스
- @Module 데코레이터는 Nest가 애플리케이션 구조를 구성하는 메타데이터 제공
- 모듈은 밀접하게 관련된 "기능 집합 구성 요소"를 구성하는 효과적인 방법
- 같은 기능에 해당하는 것들은 하나의 모든 폴더안에 넣어사용

# Controller 란?
- 컨트롤러는 들어오는 요청을 처리하고 클라이언트에 응답을 반환한다.

# NestJS 환경 설정
```
# Nest.js 설치
$> npm i -g @nestjs/cli

# Nest.js 프로젝트 생성
$> nest new swagger-study
```

Nest.js 프로젝트 생성을 완료 했으면 swagger를 사용하기 위해 dependency 를 설치해준다.
```
$> npm install --save @nestjs/swagger swagger-ui-express
```


```
nest g module boards
```

```
nest g controller boards --no-spec
```

```
nest g module boards
```

```
nest g service boards --no-spec
```

```
npm install uuid --save
```

### typeorm 모듈을 붙여준다.
1. nestjs 에 필요한 @nestjs/typeorm 모듈
2. TypeORM 에 필요한 typeorm 모듈
3. postgres 에 필요한 pg 모듈
```
npm install pg typeorm @nestjs/typeorm --save
```

