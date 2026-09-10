# 졸업증명서 템플릿 (Graduation Certificate Template)

**ActiveReportsJS Designer**로 제작된 졸업증명서(Graduation Certificate) 샘플 보고서 템플릿입니다.
`.rdlx-json` 형식으로 제공되며, 실제 학교·교육기관에서 발급하는 졸업증명서 문서 양식을 기반으로 설계되었습니다.

> 졸업증명서는 일반적으로 증명서 내에 표시할 정보의 양이 고정되어 있어 보고서의 레이아웃이 변경되지 않는 문서로, 학생 개인의 학적 정보를 공식적으로 증명하는 데 사용됩니다.

---

## 📌 주요 특징

- 증명서 내 정보량이 고정되어 있는 문서 특성에 맞춰 **고정 페이지 레이아웃(Fixed Page Layout)** 기반으로 설계
- 동일한 양식으로 **여러 졸업생의 졸업증명서를 한 번에 생성** 가능 — 졸업생 정보만 변경되며 나머지 레이아웃은 그대로 유지
- 텍스트 뒤에 **"이미지" 항목**을 배치하여 학교/기관 로고를 **배경 이미지**로 활용
- **"이미지" 항목**을 텍스트상자 앞에 배치하여 **직인 이미지**를 증명서에 삽입

---

## 🗂️ 포함된 졸업증명서 항목

| 구분 | 항목 |
|---|---|
| 학생 정보 | 졸업자 이름, 생년월일, 학과, 학번, 입학일, 졸업일, 학위등록번호 |
| 발급 정보 | 발급일, 발급 기관명, 직인 |
| 디자인 요소 | 배경 이미지 |

---

## 📄 보고서 구성 특징

| 구성 요소 | 설명 |
|---|---|
| 고정 페이지 레이아웃 | 정보량이 일정한 증명서 특성에 맞춰 레이아웃 변경 없이 일관되게 유지 |
| 배경 이미지 | 텍스트 뒤에 이미지 항목을 배치하여 학교/기관 로고를 배경으로 표시 |
| 직인 이미지 | 텍스트상자 앞에 이미지 항목을 배치하여 직인을 삽입 |
| 다중 발급 지원 | 동일 양식으로 여러 졸업생의 증명서를 일괄 생성 가능 |

---

## 🚀 사용 방법

ActiveReportsJS Viewer를 이용하여 아래와 같이 보고서를 불러올 수 있습니다.

```javascript
viewer.open("졸업증명서.rdlx-json");
```

템플릿은 **ActiveReportsJS Designer**에서 열어 자유롭게 커스터마이징(항목 추가/수정, 레이아웃 변경, 데이터 소스 연결 등)하실 수 있습니다.

---

## 🛠️ 사용 기술

- [ActiveReportsJS](https://www.mescius.co.kr/activereportsjs) Designer
- `.rdlx-json` 리포트 포맷
- 고정 페이지 레이아웃(Fixed Page Layout)
- 이미지 항목(배경 이미지 / 직인 이미지)

---

## 📝 라이선스

본 템플릿은 학습 및 참고 목적의 샘플로 자유롭게 사용 및 커스터마이징이 가능합니다.

---

## 🔖 Keywords / Tags

`ActiveReportsJS` `RDL` `rdlx-json` `Report Designer` `Reporting Tool` `보고서 템플릿` `졸업증명서` `Graduation Certificate` `증명서` `Certificate Report` `Fixed Page Layout` `고정 페이지 레이아웃` `JavaScript Reporting` `Web Reporting`
