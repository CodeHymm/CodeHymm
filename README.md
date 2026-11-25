# 차병준 | Backend & Service Developer

**프리랜서 프로젝트를 찾고 있습니다.**  
Java · Spring Boot · React · Node.js · Python

약 16년간 헬스케어, 제조, IoT 분야에서 백엔드와 웹서비스를 개발해 왔습니다. 실시간 데이터를 수집하고 처리하는 서버부터 사용자가 확인하는 웹 화면까지 만들었습니다. 최근에는 Python과 LangGraph를 활용한 AI Agent와 의료 분석 리포트 생성 기능을 개발했습니다.

이 GitHub에서는 **시스템 구조, 데이터 흐름, 기술 선택의 이유**를 중심으로 설계 자료를 공유합니다. 아래 대표 프로젝트는 설계 문서 중심의 포트폴리오이며, 구현 코드는 공개 범위에 포함하지 않습니다.

## 대표 설계 포트폴리오

### [의료 리포트 AI Agent](https://github.com/CodeHymm/ai_agent_backend)

의료 분석 데이터를 조회하고, 필요한 컨텍스트를 구성해 리포트를 생성하는 AI Agent 설계입니다.

- LangGraph 기반 리포트 생성 워크플로와 단계별 역할
- ClickHouse 데이터 조회와 RAG 컨텍스트 구성
- 데이터 조회, 리포트 생성, 결과 검증의 책임 분리

`Python` `FastAPI` `LangGraph` `ClickHouse` `RAG`



### [VCP-X 제조 데이터 교환 플랫폼](https://github.com/CodeHymm/vcp_data_platform)

여러 공장의 제조 데이터를 표준화하고, 구독 조건에 따라 필요한 기업에 주기적으로 전달하는 데이터 플랫폼 설계입니다.

- OPC UA 기반 공장 데이터 수집과 Avro 표준화·AAS 모델링
- MSK·SNS·SQS·Lambda 기반 구독 데이터 전달 및 고객 API 연계
- DPP·PCF 활용 데이터 구성과 고객·공장별 S3 데이터 보관

`Java` `Spring Boot` `Python` `Kafka / MSK` `Avro` `AAS` `AWS Lambda`

### [제조 데이터 Data Lake](https://github.com/CodeHymm/manufacturing-datalake)

반도체 제조 장비 로그와 환경 센서 데이터를 S3에 모으고, Parquet으로 변환해 조회·분석할 수 있게 하는 Data Lake 설계입니다.

- MSK·Kinesis·Lambda 기반 장비 로그·센서 데이터 수집과 S3 Raw 적재
- Spark 기반 Glue ETL의 정제·Parquet 변환과 일자·장비 단위 파티셔닝
- Glue Data Catalog·Athena 조회, QuickSight 리포트, Airflow 워크플로 구성

`Python` `Spark` `AWS Glue` `S3` `Parquet` `Athena` `Airflow`


## 개발 경험

| 분야 | 주요 경험 |
| --- | --- |
| 백엔드 | Java, Spring Boot, Python, FastAPI, REST API, 외부 시스템 연동 |
| 웹서비스 | React, Next.js, Node.js 기반 CMS, B2B 데이터 교환, 리포트 웹서비스 |
| 실시간 데이터 | Netty, Kafka, ActiveMQ Artemis, Redis·Jedis 기반 데이터 교환 |
| 데이터 플랫폼 | ClickHouse, TimescaleDB, MySQL, Airflow, Flink, ETL |
| AI 서비스 | LangGraph, RAG, LLM, Amazon Bedrock |
| AWS 서비스 | Amazon MSK, S3, SNS, SQS, AWS Lambda, Amazon Bedrock |
| 인증·인프라 | JWT, Keycloak, Docker |



## 프로젝트 협업

Java/Spring 또는 Python 기반 백엔드, React·Node.js 웹서비스, AI Agent, 실시간 데이터 플랫폼 프로젝트에 참여하고자 합니다.

- **계약 형태:** 프리랜서 / 프로젝트 계약
- **투입 가능일:** 협의 가능
- **근무 선호 지역:** 서울 강남, 판교, 분당, 수원, 동탄
- **문의:** 8mega@naver.com

프로젝트의 개발 범위와 일정을 보내주시면 참여 가능 여부를 말씀드리겠습니다.
