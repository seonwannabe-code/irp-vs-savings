
# 개인형IRP vs 적금 비교 (모바일/브라우저용)

단일 HTML로 실행되는 비교 도구입니다. GitHub Pages에 올리면 스마트폰에서 링크만으로 바로 사용 가능합니다.

## 배포(깃허브 페이지)
1. GitHub에서 새 레포지토리 생성 (예: `irp-vs-savings`), Public 선택
2. 이 폴더의 파일들을 업로드 (`index.html`, `README.md`)
3. 레포 **Settings → Pages**에서
   - Source: **Deploy from a branch**
   - Branch: **main / root** 저장
4. 몇 분 후 배포 URL 생성
   - `https://<your-username>.github.io/irp-vs-savings/`
   - 위 주소를 스마트폰 브라우저에서 열면 실행됩니다.

## 로컬 테스트
더블클릭으로 `index.html`을 브라우저에서 열면 동작합니다.

## 기능
- 월 불입액/개월수/연이자율/적금 과세율/개인형IRP 세액공제율/개인형IRP 연 한도 입력
- 월초 불입 **고정**
- 적금(세후) vs 개인형IRP(이연수익+세액공제) **1년 효과 비교**
- 막대형 시각화(순수 CSS/JS)

> *주의: 단순화된 가정(연 단리, 과세이연, 세액공제율·한도 고정)으로 구현되어 실제 결과와 다를 수 있습니다.
