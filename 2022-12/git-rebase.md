# 브랜치 전략 ?

(제대로 된)협업은 처음이라...

PR을 리뷰받고, 머지를 하고 있는 요즘...

과거에는 merge commit 을 만드는 과정으로만 작업했었는데, 최근에 squash and commit 으로 전략을 수정했다. 

그러다보니 이제껏 내 이름을 딴 브랜치 하나에서 모든 작업을 쭉~~ 하고있었던 나는 가면 갈수록 내 PR에서 과거 commit 이 딸려들어오면서 거대해지는 것을 목격했다...

이건 당연히 원하지 않는 결과였다.

한번 정리가 필요하다.



git cherry-pick <1층>^..<2층>

최근에 PR 을 리뷰받고 머지하는 걸 여러번 경험했었는데
