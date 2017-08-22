# Git에 대한 설명
Git을 사용하면서 유용한것을 정리한다.

## GitPage를 docs로 활용
Documentation 을 만들고자 할 경우(iOS일 경우로 설명한다)

- Reporgitory에 /docs가 꼭 존재해야만 한다.

```(Fail 예)
  1. Submodule로 /docs로 존재시 fail
```

## Git Submodule 변경
Git의 Reporgitory의 name은 변경하지 않고 local Reporgitory의 명칭 만 변경 할수 있다.

```(예)
 .gitmodule 파일을 열면

 [submodule "swift_docs"]
 	path = swift_docs --> 원하는 명칭으로 변경 하면 된다.
 	url = https://github.com/EJUNBLACK/swift_docs.git
 ```
