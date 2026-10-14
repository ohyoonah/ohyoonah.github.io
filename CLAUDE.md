# ohyoonah.github.io

개인 기술 블로그. Jekyll + Chirpy 테마, GitHub Pages로 배포.

## 프로젝트 구조

- `_posts/` — 블로그 포스트 (파일명: `YYYY-MM-DD-title.md`)
- `_tabs/` — 사이드바 탭 페이지 (about, archives, categories, tags)
- `_data/contact.yml` — 사이드바 소셜 링크
- `_data/authors.yml` — 포스트 작성자 정보
- `assets/img/` — 이미지 파일
- `_config.yml` — 사이트 설정

## 사이트 정보

- 제목: ohyoonah.dev
- 부제목: 개발 기록
- 소유자: ohyoonah
- GitHub: https://github.com/ohyoonah
- 이메일: dhdbsdk33@gmail.com

## 로컬 실행

```bash
bundle exec jekyll serve
```

## 배포

`master` 브랜치에 푸시하면 `.github/workflows/pages-deploy.yml`을 통해 GitHub Pages에 자동 배포.
