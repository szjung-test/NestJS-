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

