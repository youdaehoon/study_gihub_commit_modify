#### update log
05-26 

# study_gihub_commit_modify
## 목적 
원격저장소에 저장된 commit을 취소하는 연습
## 계기
github는 너무나 친절합니다. firebase에 사용되는 apikey를 올렸더니 알려주더군요.
repository를 private로 돌리고 허둥지둥 firebase의 해당 앱을 삭제하고, 새로운 key를 발급받았습니다.
해당 repository에 누군지 모를 watch도 찍혀있더군요. 
급한 불을 껏으니 github에 남아있는 commit을 삭제하여 나의 단점은 숨기고, 내 프로젝트는 자랑하기위해 조치가필요합니다.
하지만, key를 삽입하는 commit이후 6개(실제로 맞는 숫자아님)의 커밋이 있더군요. 
그런고로 연습하고, 기록하기 위하여 해당 repository를 만듭니다.
## 전략 list
1. interactive rebase 명령어 입력
```
git rebase -i <commit>
```




