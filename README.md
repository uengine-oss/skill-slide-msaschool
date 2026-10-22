# MSASchool Purple 슬라이드 스킬

기존 발표자료를 MSASchool의 흰 바탕·보라색 강조 스타일로 전환하거나, 같은 스타일의 새 발표자료를 만드는 Codex 스킬입니다. 편집 가능한 표와 텍스트, 원본 스크린샷을 유지합니다.

![MSASchool Purple 미리보기](assets/preview.png)

## 설치

Codex에 다음과 같이 요청합니다. 비공개 저장소 인증은 필요하지 않습니다.

```text
$skill-installer https://github.com/uengine-oss/skill-slide-msaschool
```

수동 설치는 저장소 전체를 개인 스킬 폴더로 복제합니다.

```sh
git clone https://github.com/uengine-oss/skill-slide-msaschool.git ~/.agents/skills/artifact-template-msaschool-purple
```

설치 후 스킬이 표시되지 않으면 Codex를 다시 실행합니다. 이 스킬은 Presentations 기능을 함께 사용하는 환경을 전제로 합니다.

## 사용 예시

```text
$artifact-template-msaschool-purple
첨부한 PPTX의 내용과 장수를 유지하면서 MSASchool 스타일로 바꿔줘.
```

```text
MSASchool 스타일로 마이크로서비스 교육과정 제안서 10장을 만들어줘.
최종 결과는 편집 가능한 PPTX로 전달해줘.
```

## 포함 자료

- `SKILL.md`: 작성·변환·검수 지침
- `references/`: 디자인 규격, 레이아웃 선택 지도, 참조 파일 정보
- `assets/reference.pptx`: 편집 가능한 스타일 참조 자료
- `assets/msaschool-original.pdf`: 원래 시각 기준 자료
- `assets/`: 로고, 표지 배경, 미리보기
- `agents/openai.yaml`: Codex 표시 정보

참조 자료의 고객명·수치·사례는 새 발표 내용으로 재사용하지 않습니다. 서체는 포함되어 있지 않으며 디자인 규격을 참고해 사용 환경에서 준비합니다. 저장소 공개가 포함된 브랜드·사진·참조 자료의 별도 이용허락을 의미하지는 않습니다.

## 업데이트

수동 설치한 경우 설치 폴더에서 `git pull`로 업데이트합니다.
