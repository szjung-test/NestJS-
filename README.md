# NestJS 환경 설정

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

