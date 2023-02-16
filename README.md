# 안드로이드 프로젝트 구조

![image](https://user-images.githubusercontent.com/105768122/219377376-73d8d08a-552e-4369-a8ad-711180b1cce5.png)

프로젝트 구조로 가장 크게
app과 Gradle 파트로 나눌수 있다.

## 1. app
  1. manifests (환경 설정)
  어플리케이션의 기본 설정과 권한 정보, activity 정보를 담당한다.
  app/manifests/AndroidManifest.xml 경로에서 작성한다.

  2. java (소스 코드)
  앱의 동작을 담당하는 java나 kt 확장자의 코드가 여기에 담긴다.

  3. res(리소스)
  코드 외의 리소스로 이미지, ui 문자열, xml 레이아웃 등이 들어간다.

## 2. Gradle

  build.gradle에서 SDK버전이나 테스트, 빌드 컴파일 등을 관리 할 수 있다.
  ![image](https://user-images.githubusercontent.com/105768122/219381524-41f718b0-782f-437b-85e1-2aca82a96e5f.png)

  같은 파일의 dependencies 부분에서 의존성 관리가 가능하다.
  쉽게 표현하면 다른 사람의 라이브러리를 가져와 사용할 수 있다는 것이다.
  ![image](https://user-images.githubusercontent.com/105768122/219382901-dc4b7e46-50c1-4f7a-b5a4-a880e0ca6bf6.png)

