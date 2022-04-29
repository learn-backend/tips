# Tips Repository



## Git user.name / user.email Proeject별 설정 방법

Git의 기존 user.name 및 user.email은 미설정시 전역(global) 설정을 바라보는 것 같다.

그러나 아래 방법으로 하면, 우선순위가 프로젝트 설정으로 동작하는듯 하다.

> 파일을 위에서 부터 읽어오다가 덮어쓰는게 아닐까 추측..

```bash
cd ~/{project root path}
git config user.name "GitHub ID"
git config user.email "Email@Email.com"

// 확인 방법
git config --list
```



**미설정시**

<img width="490" alt="CleanShot 2022-04-29 at 13 52 15@2x" src="https://user-images.githubusercontent.com/37217320/165886916-fa794dbd-6bee-4019-bd40-9cd7d0d19eec.png">

**설정시**

<img width="543" alt="CleanShot 2022-04-29 at 13 51 12@2x" src="https://user-images.githubusercontent.com/37217320/165886828-441a9c88-efff-4ee3-8793-290dffc20923.png">

> Reference: [Git config 설정 (계정설정)](https://goodtogreate.tistory.com/entry/Git-config-%EC%84%A4%EC%A0%95-%EA%B3%84%EC%A0%95%EC%84%A4%EC%A0%95)
