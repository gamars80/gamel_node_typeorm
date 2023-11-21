# Awesome Project Build with TypeORM

Steps to run this project:

1. Setup database settings inside `data-source.ts` file
2. Run `npm run dev` command


# TypeORM 사용
    tsconfig.ts : 타입스크립트로 짜인 코드를 javascript로 콤파일 하는 옵션 설장 파일
    npx tsc --init 하면 생성됨

    tsconfig.json 에 esModuleInterop: true로 추가

    morgan모듈 설치: log 관리

    ts-node : Node.js 상에서 타입스크립트 콘트롤러를 통하지 않고 직접 타입스크립트를 실행하는 역할

# 데이터 베이스
    npm install pg typeorm reflect-metadata --save

    reflect-metadata 모듈 : @어노테이션 사용응 위한

    pg 모듈: postgres 데이터베이스 드라이버

    npx typeorm init : data-source.ts 생성 (데이터베이스 접근을 위한 옵션 설정들)

# Docker 설치
    docker-compose.yml 생성

    docker desktop 떠있는 상태로 프로젝트에서 docker-compose up 명령어 실행

    pgAdmin 설치 : postgres db 매니저 툴

    

