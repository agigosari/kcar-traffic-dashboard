# 📊 K Car 통합 트래픽 & UTM 구매전환 대시보드

K Car 온라인 광고 성과, 트래픽 추이 및 UTM별 구매 전환 행동을 일자별/월별로 통합 분석하는 인터랙티브 웹 대시보드입니다.

---

## 🌐 대시보드 바로보기 (GitHub Pages)

- 🔗 **최신 통합 대시보드 (메인)**: [https://agigosari.github.io/kcar-traffic-dashboard/](https://agigosari.github.io/kcar-traffic-dashboard/)
- 🔗 **UTM 구매전환 & 광고비 리포트**: [https://agigosari.github.io/kcar-traffic-dashboard/ad_spend_report_10weeks.html](https://agigosari.github.io/kcar-traffic-dashboard/ad_spend_report_10weeks.html)
- 🔗 **레거시 마케팅 대시보드 (v1)**: [https://agigosari.github.io/kcar-traffic-dashboard/traffic_dashboard_v1.html](https://agigosari.github.io/kcar-traffic-dashboard/traffic_dashboard_v1.html)

---

## 🎯 3대 핵심 탭 구성

1. **🎯 UTM 구매전환 (월별/Daily - 맨 앞장)**
   - **대상 기간**: 2025년 7월 ~ 2026년 9월 (총 15개 월 전체 탐색)
   - **좌측 고정 컬럼**: `매체` | `최종 UTM` | `ON/OFF 일자`
   - **9대 구매전환 이벤트**:
     - 온라인구매(상담후결제) - 접수완료
     - 온라인구매(접수시도) - 온라인바로구매버튼클릭
     - 온라인구매(주문신청) - 명의자및배송정보입력
     - 온라인구매(즉시결제) - 결제설계 / 결제시작 / 결제완료
     - 전화하기버튼(모바일) / 직영점방문예약하기 / 오프라인구매
   - **집계 모드**: 발생 건수(Totals) 및 월간 중복 100% 제거 순수 유니크 유저(Uniques, Amplitude `seriesCollapsed` 기준)
   - **추이 모달**: 각 UTM별 29일간 일자별 발생 상세표 및 Chart.js 시각화

2. **📊 주간 일평균 (최근 10주)**
   - 주간 일평균 광고비 대비 Paid UV 및 Paid 유효고객 상관관계 분석
   - 5대 매체별 상세 집행 추이 및 2종 차트 제공

3. **📅 일자별 추이 (최근 90일 Daily)**
   - 2026년 6월 30일 ~ 9월 27일까지 90일간의 일별 광고비 및 트래픽 추이
   - 일별 듀얼 Y축 트렌드 차트 및 매체별 집행 차트 제공
