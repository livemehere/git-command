# git-command

- 이미 commit된 파일을 제거하는 방법(gitignore에 작성하지 못했을 때 하는 방법이다)

```bash
git rm [filename] //local
git rm --cached -r [filename] //remote  -r : 폴더 하위 모두삭제 (생략하면 특정파일)
```

- 하고나서 push
