# Codeigniter를 이용한 Restful API 개발

## 내용

작품(=상품) 상세 페이지를 구성하는 데이터를 출력하는 Restful API를 개발하는 것이 목적

### 작품 상세 참고 URI

* https://www.idus.com/w/product/7dbe1c8b-41af-460c-ad88-b791a0552d28
* https://www.idus.com/w/product/074782b0-7a5e-4eff-960f-117871ec7f24
* https://www.idus.com/w/product/12b83a5e-e621-4de9-aef6-61b0d3e6104b
* https://www.idus.com/w/product/2b89cd03-897d-47cd-8cfc-5e92f0b4329f

작품이 판매 종료되거나 삭제되는 경우가 있습니다. 더 많은 작품은 https://www.idus.com 를 방문하여 보실 수 있습니다. 

## 개발에 사용할 소프트웨어

* Apache HTTPD
* PHP
* Codeigniter
* MySQL
* Git
* Docker
* Docker Compose

## 요구 사항

* 소프트웨어의 버전은 어떤 버전을 사용해도 관계 없음.
* 모르는 기술은 인터넷 검색 또는 기술 서적 등을 통해 사용 방법을 터득.
* 개발 시간이 부족할 경우 작품 상세 내용을 모두 출력할 필요는 없으며 중요하다고 생각되는 것을 우선하여 출력.
* API 출력 형식은 Json으로 출력.
* 개발 결과물은 github, bitbucket, gitlab 등의 링크로 제출.

## 필수 출력 항목

* 작품명(상품명)
* 작품 이미지 URI 리스트
* 작가명(판매자명)
* 작가 프로필 이미지 URI
* 작품 가격
* 작품 할인 가격
* 작품 할인율
* 작품 정보
* 카테고리명
* 키워드 리스트
* 구매 후기 리스트
    * 구매자명
    * 구매자 프로필 이미지 URI
    * 작성일자
    * 별점
    * 구매 후기 내용

## 추가(옵션) 출력 항목

아래 항목은 반드시 출력하지 않아도 되지만 출력할 경우 이에 대한 가산점이 있습니다.

* 댓글 리스트
* 판매 중인 다른 작품 리스트
* 그 외 OOO(카테고리) 인기 작품 리스트

## 예외

개발에 사용할 소프트웨어를 사용하여 개발하는 과정에서 어려움이 있는 경우 해당 기술을 제외하고 완성해도 됩니다.

## 개발환경 구성 : [링크](./docs/dev_env_setting.md)

## 문의

궁금한 점이 있다면 ziplus4@backpac.kr 로 연락주시기 바랍니다.
