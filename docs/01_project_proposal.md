# Project Proposal

## Business Scenario

Olist는 다양한 판매자(Seller)와 고객(Customer)을 연결하는 브라질 전자상거래 플랫폼이다.

플랫폼이 성장함에 따라 경영진과 각 부서는 매출, 고객, 상품 및 배송 성과를 지속적으로 모니터링하고, 데이터를 기반으로 빠르고 효과적인 의사결정을 내릴 수 있는 환경이 필요하다.

본 프로젝트는 Olist 전자상거래 데이터를 활용하여 핵심 비즈니스 지표(KPI)를 설계하고, 이해관계자(Stakeholder)별 Dashboard를 구축하는 것을 목표로 한다.

또한 단순히 KPI를 시각화하는 것에 그치지 않고, Dashboard를 기반으로 주요 비즈니스 이슈를 분석하고 개선 방향을 제안함으로써 실제 비즈니스 의사결정을 지원하는 Business Intelligence Dashboard를 구현하고자 한다.

---

# Stakeholders

본 Dashboard는 다음과 같은 이해관계자를 대상으로 설계하였다.

### Executive Team (경영진)

- 전체 비즈니스 성과 모니터링
- 핵심 KPI 확인
- 전략적 의사결정 지원

### Sales Team (영업팀)

- 상품 및 카테고리 성과 분석
- 지역별 매출 분석
- 판매 전략 수립 지원

### Marketing Team (마케팅팀)

- 고객 분포 및 구매 패턴 분석
- 고객 행동 분석
- 마케팅 전략 수립 지원

### Logistics Team (물류 운영팀)

- 배송 효율성 모니터링
- 배송 지연 분석
- 배송 비용 분석 및 운영 효율 개선

---

# Business Questions

각 이해관계자가 실제 비즈니스에서 궁금해할 수 있는 질문을 기반으로 Dashboard를 설계하였다.

## Executive Team

- 우리 비즈니스는 지속적으로 성장하고 있는가?
- 핵심 KPI는 시간에 따라 어떻게 변화하고 있는가?
- 현재 전반적인 사업 성과는 어떠한가?

---

## Sales Team

- 어떤 상품 카테고리가 가장 높은 매출을 창출하는가?
- 어떤 상품이 가장 높은 매출에 기여하는가?
- 어느 지역이 매출에 가장 크게 기여하는가?

---

## Marketing Team

- 고객은 어느 지역에 집중되어 있는가?
- 지역별 고객 구매금액은 어떻게 다른가?
- 재구매 고객의 비율은 어느 정도인가?

---

## Logistics Team

- 평균 배송기간은 어느 정도인가?
- 배송 지연이 많이 발생하는 지역은 어디인가?
- 배송비가 높은 지역 및 상품 카테고리는 무엇인가?
- 배송 성과와 고객 리뷰 평점은 어떤 관계가 있는가?

---

# Project Goal

Olist 데이터를 활용하여 핵심 비즈니스 KPI를 설계하고, 이해관계자별 Dashboard를 구축하여 비즈니스 성과를 효과적으로 모니터링하고 데이터 기반 의사결정을 지원하는 것을 목표로 한다.

또한 Dashboard를 기반으로 주요 비즈니스 이슈를 분석하고, 데이터에 근거한 비즈니스 인사이트와 개선 방향을 제안한다.

---

# Expected Deliverables

본 프로젝트의 최종 산출물은 다음과 같다.

- Executive Dashboard
- Sales Dashboard
- Customer Dashboard
- Logistics Dashboard
- KPI Definition Document
- Business Analysis Report
- Business Recommendations

---

# Success Criteria

본 프로젝트는 다음 기준을 만족하는 것을 목표로 한다.

- 핵심 KPI를 직관적으로 확인할 수 있어야 한다.
- 이해관계자별로 필요한 비즈니스 정보를 효과적으로 제공할 수 있어야 한다.
- 필터(Filter)를 활용하여 다양한 관점에서 데이터를 탐색할 수 있어야 한다.
- Dashboard를 기반으로 주요 비즈니스 인사이트를 도출할 수 있어야 한다.
- 데이터 기반의 개선 방향을 제안할 수 있어야 한다.

---

# Project Scope

본 프로젝트에서는 다음 영역을 중심으로 분석을 수행한다.

- Sales Performance
- Customer Performance
- Product Performance
- Regional Performance
- Delivery Performance
- Freight Cost Analysis
- Customer Review Analysis

---

# Limitations

본 데이터셋은 다음과 같은 한계를 가진다.

- 재고(Inventory) 데이터가 존재하지 않는다.
- 웹/앱 이벤트 로그 데이터가 존재하지 않는다.
- 마케팅 채널 및 캠페인 데이터가 존재하지 않는다.
- 상품 원가 및 운영 비용 데이터가 없어 정확한 Profit 분석은 수행할 수 없다.
- A/B Test 및 실험 데이터가 존재하지 않는다.

---

# Dashboard Overview

본 프로젝트는 이해관계자의 목적에 맞추어 총 4개의 Dashboard로 구성한다.

## 1. Executive Dashboard

### 목적

- 전체 비즈니스 성과를 한눈에 파악
- 핵심 KPI 모니터링
- 월별 성과 추이 확인

### 주요 KPI

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value (AOV)
- Average Review Score
- Monthly Revenue Growth

---

## 2. Sales Dashboard

### 목적

- 상품 및 카테고리 성과 분석
- 지역별 매출 분석
- 판매 성과 모니터링

### 주요 KPI

- Category Revenue
- Top Products
- Revenue by State
- Monthly Sales
- Order Volume

---

## 3. Customer Dashboard

### 목적

- 고객 분포 및 구매 패턴 분석
- 지역별 고객 성과 분석
- 고객 행동 파악

### 주요 KPI

- Customer Distribution
- Revenue by Customer
- Average Customer Spending
- Repeat Purchase Rate

---

## 4. Logistics Dashboard

### 목적

- 배송 효율성 분석
- 배송 비용 분석
- 고객 만족도 분석

### 주요 KPI

- Average Delivery Time
- Late Delivery Rate
- Freight Cost
- Review Score
- Delivery Performance

---

# Expected Outcome

본 프로젝트는 단순히 Dashboard를 제작하는 것을 목표로 하지 않는다.

Dashboard를 통해 비즈니스 현황을 빠르게 파악하고, Business Analysis를 통해 성과 변화의 원인을 분석하며, 최종적으로 데이터 기반의 의사결정을 지원할 수 있는 Business Intelligence Dashboard를 구축하는 것을 목표로 한다.
