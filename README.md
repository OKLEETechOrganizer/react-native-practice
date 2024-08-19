# react-native-practice

## [프로젝트 개요]
리액트 네이티브와 관련된 프로젝트 리포지토리

브랜치별로 다양한 프로젝트를 구성할 예정 

## [개발환경]
- node: v20.12.1
- java: 17(openjdk ver)

## [발생한 문제와 해결]
#### cocoaPods 설치 오류
- cocoaPods는 기존에 설치된 ruby 버전으로는 설치가 되지 않는다.
  - 다음의 방법으로 설치함
    ```
    $ sudo gem install activesupport -v 6.1.7.7
    $ sudo gem install cocoapods
    ```
    
