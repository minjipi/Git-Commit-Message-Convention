## Git Commit Message Convention

- **FIX** : 버그, 오류 해결<br>
`[FIX] #10 - multipart image upload error`

- **FEAT**  : 새로운 기능 구현<br>
`[FEAT] #11 - kakao login`

- **ADD** : Feat 이외의 부수적인 코드 추가/라이브러리 추가/새로운 class 생성<br>
`[ADD] #11 - Cabinet package`<br>

- **DEL**  : 쓸모없는 코드 삭제<br>
`[DEL] #12 - unnecessary import package`

- **DOCS**  : README나 wiki 등 개정<br>
`[DOCS] #13 - update readme`

- **REFACTOR** : 내부 로직은 변경 하지 않고 기존의 코드 개선하는 리팩토링 시<br>
`[REFACTOR] #15 - JDBC connection`

- **CHORE** : 그 이외의 잡일/ 버전 코드 수정, 패키지 구조 변경, 파일 이동, 가독성이나 변수명, reformat 등 <br>
`[CHORE] #20 - delete unnecessary import package`<br>
`[CHORE] #21 - reformat ProductController`


- **MOD** : xml 파일 수정 시 <br>
`[MOD] #30 - use constraintlayout in activity_main.xml`

- **TEST** : 테스트 코드 추가

<br>

### ex)
```
[접두어] #이슈번호 - 내용<br>
세부내용<br>
각주<br>
```

```
[FEAT] #11 - google login
- Use Firebase Auth (http://example.com/reference)
- Need refactor code
See Also : #100, #120
```


[![WrittenBy](https://img.shields.io/badge/Written%20by-minjipi-pink.svg)](https://github.com/minjipi/)
