# Nuber Eats

The Frontend of Nuber Eats Clone

1. Frontend Setup:

   - CRA 프로젝트 생성
     - `npx create-react-app nuber-eats-frontend --template=typescript`
   - [TailwindCSS](https://tailwindcss.com/docs/installation) Setup

     - utility-first CSS는 각 class가 담당할 스타일을 미리 정의하고 필요한 class들을 조합해서 사용
     - 패키지 설치: `npm install tailwindcss postcss autoprefixer`
     - VScode Extension 설치: `Tailwind CSS IntelliSense`
     - postcss로 tailwindCSS 빌드하기:
       ```bash
       "scripts": {
           "tailwind:build": "tailwind build ./src/styles/tailwind.css -o ./src/styles/styles.css",
           "start": "npm run tailwind:build & react-scripts start",
           ...
           }
       ```

   - [Apollo](https://www.apollographql.com/docs/react) Setup
     - Chrome Extension 설치: `Apollo Client Developer Tools`
