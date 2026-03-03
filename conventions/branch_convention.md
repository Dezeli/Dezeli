# 🌿 Branch Convention
기계적으로 push하지 말고 commit과 push를 절대적으로 구분하자.

1. **main**
   - **원칙적으로 메인 브랜치에 Merge하지 않는다. (릴리스 브랜치)**
   - 메인 브랜치는 팀원 모두의 동의를 얻어야만 업데이트 가능하다.

2. **develop**
   - 개발 서버에 올릴 수 있는 수준만 Merge 한다.
   - Merge 할 때도 리뷰는 거쳐서 진행해야 한다.

3. **feature**
   - Feature 브랜치는 기능 단위로 사용하며 `feature/기능명` 형식으로 사용한다.

4. **hotfix**
   - Hotfix 브랜치는 빠르게 고쳐야 할 사항이 있을 때 사용한다.
   - 이전 Hotfix 브랜치가 해결되지 않은 경우 다른 Hotfix 브랜치를 열지 않는다.

5. **release**
   - 배포용 브랜치로 활용한다.
