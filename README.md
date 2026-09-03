# 로고 · 명함 디자인 포트폴리오

한 페이지짜리 정적 사이트입니다. 서버가 필요 없습니다.

    index.html    페이지
    img/          이미지

## 올리는 법 — GitHub Pages

    git init
    git add -A
    git commit -m "포트폴리오 사이트"
    git branch -M main
    git remote add origin https://github.com/<계정>/<저장소>.git
    git push -u origin main

그 다음 저장소 **Settings → Pages** 에서
Source 를 `Deploy from a branch`, 브랜치를 `main` / `(root)` 로 둡니다.
몇 분 뒤 `https://<계정>.github.io/<저장소>/` 에서 열립니다.

## 고칠 때

이 폴더를 손으로 고치지 마세요. **다시 만들면 덮어써집니다.**
원본은 `J:\design-gen` 에 있고, 이렇게 다시 짓습니다.

    python make_portfolio_viewer.py    # viewer.html
    python make_site.py                # 이 폴더

## ⚠ 넣으면 안 되는 것

`config.json` 에는 살아 있는 API 키가 들어 있습니다.
**이 폴더에 복사하지 마세요.** `.gitignore` 가 막고 있지만
이름을 바꿔 넣으면 그물을 빠져나갑니다.

표시된 상호 · 이름 · 연락처는 실제 고객이 아닌 예시입니다.
