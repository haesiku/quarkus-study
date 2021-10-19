# Quarkus-study

## Quarkus 
kubernetes와 통합되어 있는 cloud native framework
GraalVM과 OpenJDK 핫스팟에 최적화된 kubernetes native application 개발 지원
hibernate, kubernetes, Apache Camel, Eclipse Vert.x 기수 기반

## Quarkus 장점
doker, kubernetes와 쉬우 통합, 빠른 시작시간, 낮은 상주 세트 크기(RSS) 메모리, 개발자 생산서 향상

### 개발자 친화적
### Kubernetes와 통합
### Memory, 첫 응답시간


Quarkus Project 만들기
Maven, Gradle, https://code.quarkus.io or https://code.quarkus.redhat.com, VS Code

개발자 모드(Developeer mode)
background compile을 통해 hot deployment 가능: java파일 또는 resource를 변경하고 browser 새로고침하면 변경사항ㅇ 자동으로 적용됨
'''
./mvnw compile quarkus:dev
