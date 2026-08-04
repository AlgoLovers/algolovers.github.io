---
title: 워킹대디 개인정보처리방침
---

# 워킹대디 개인정보처리방침

시행일: 2026-07-27 · 최종 개정일: 2026-08-04

워킹대디(이하 "앱")는 학부모가 학교 문서(주간학습안내·가정통신문)를 사진/파일로
등록하면 인공지능으로 숙제·준비물·행사·시험 일정을 정리해 주는 안드로이드 앱입니다.

## 한눈에 보기

- 계정·로그인이 없고, 이름·연락처·위치·광고식별자를 수집하지 않습니다.
- 개발자는 **서버를 운영하지 않습니다.** 일정·자녀 정보·문서는 이용자 기기 안에만 저장됩니다.
- 광고와 제3자 분석(애널리틱스) 도구를 사용하지 않습니다.
- **다만 문서 자동 정리 기능을 쓰면, 이용자가 등록한 문서가 Google Gemini API로 전송됩니다.**
  이 전송은 이용자가 직접 발급해 입력한 API 키로 이루어지며, 아래 4항에 자세히 적었습니다.
  자동 정리를 쓰지 않고 일정을 직접 입력하면 문서는 어디로도 전송되지 않습니다.

## 1. 처리하는 정보
- **이용자가 등록한 학교 문서**: 사진(이미지) 또는 PDF 파일.
- **문서에서 추출된 일정 정보**: 제목·날짜·과목·설명 등 텍스트.
- **이용자가 입력한 정보**: 자녀 이름/학년, 자유 태그, 수동으로 추가한 일정.
- **Gemini API 키**: 이용자가 직접 발급해 입력한 키.
- 앱은 계정 가입을 요구하지 않으며, 이름·연락처·위치·광고식별자 등을 수집하지 않습니다.

## 2. 처리 목적
등록한 문서에서 일정을 추출·정리하고, 알림·위젯으로 챙길 것을 안내하기 위함입니다.

## 3. 저장 위치 (로컬 우선)
- 위 모든 정보(문서·일정·자녀 정보·API 키)는 **이용자 기기 내부에만** 저장됩니다.
- 앱 개발자는 **별도의 서버를 운영하지 않으며**, 위 정보를 개발자 서버로 전송·보관하지
  않습니다.

## 4. 제3자 제공·처리 위탁 (중요)
문서 자동 추출을 위해, 이용자가 등록한 **문서 이미지/파일과 API 키가 Google의 Gemini
API로 전송**되어 처리됩니다. 해당 처리는 Google의 개인정보처리방침을 따릅니다.
- Google 개인정보처리방침: https://policies.google.com/privacy
- Gemini API 이용약관: https://ai.google.dev/gemini-api/terms
- 무료 등급 사용 시 데이터 취급 정책은 Google 약관을 확인하세요(모델 개선에 활용될 수
  있음). 민감정보가 우려되면 유료 등급 또는 문서 마스킹을 고려하세요.

## 5. 접근 권한
- **카메라**: 문서를 직접 촬영할 때만 사용.
- **파일/미디어 접근**: 이용자가 선택한 문서를 불러올 때만 사용.
- **알림(Android 13+)**: 아침 브리핑·마감 리마인더 발송.
각 권한은 해당 기능을 쓸 때만 요청하며, 거부해도 다른 기능은 사용할 수 있습니다.

## 6. 보관 기간 및 파기
정보는 이용자가 앱에서 삭제하거나 앱을 삭제하면 즉시 파기됩니다. 별도 보관본은 없습니다.
앱 안에서 **설정 → 전체 초기화**로 모든 데이터를 한 번에 지울 수 있습니다.

## 7. 이용자의 권리
앱 내에서 일정·자녀 정보·API 키를 언제든 조회·수정·삭제할 수 있습니다.

## 8. 아동의 개인정보
앱은 학부모(보호자)가 사용하는 것을 전제로 하며, 아동에게서 직접 개인정보를 수집하지
않습니다. 자녀 이름·학년은 보호자가 입력하는 값이며 기기 안에만 저장됩니다.

## 9. 문의처
개인정보 관련 문의: sangchul0714@gmail.com

## 10. 고지
본 방침은 관련 법령·서비스 변경에 따라 개정될 수 있으며, 개정 시 본 문서에 반영합니다.

---

# WorkingDad Privacy Policy (English)

WorkingDad is an Android app that turns school documents (weekly plans, newsletters)
into a schedule of homework, supplies, events, and exams for parents.

- No accounts, no sign-in. We never collect names, contact details, location, or advertising IDs.
- **The developer runs no server.** Schedules, child names, and documents stay on the user's device.
- No ads. No third-party analytics.
- **However, when the automatic extraction feature is used, the document the user selects is sent to
  Google's Gemini API**, using an API key the user obtained and entered themselves. That processing is
  governed by Google's Privacy Policy (https://policies.google.com/privacy) and the Gemini API Terms
  (https://ai.google.dev/gemini-api/terms). On the free tier, submitted content may be used to improve
  Google's models — see Google's terms. Users who prefer not to send documents can enter schedules
  manually; nothing is transmitted in that case.
- Permissions (camera, file access, notifications) are requested only when the related feature is used.
- All data is removed when the user clears it in the app (**Settings → Reset all data**) or uninstalls it.
- We do not knowingly collect personal information from children; the app is intended for parents.

---

문의 / Contact: sangchul0714@gmail.com
시행일 / Effective date: 2026-07-27 (개정 / Revised: 2026-08-04)
