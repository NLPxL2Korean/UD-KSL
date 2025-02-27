## dep: Unspecified dependency relation

### Definition
`dep` refers to sentence components that are grammatically or semantically incorrect and cannot be assigned a specific UD tag.

---

### Characteristics
- The dep tag is assigned when a component is ungrammatical or semantically unclear. It is typically parsed as a dependent of the root.
- The dep tag serves as a fallback option in the UD scheme. If the erroneous component is a noun, it is tagged as advmod; if it is a predicate, it is tagged as advcl. If the part of speech is unclear, it is tagged as dep.

---

### Examples
- 그 영화의 주제는 어떤 살인자가 <ins>**찹은**</ins> 것이 어렵다.
- 선생님께서 학생들을 한 명씩 소개하고 <ins>**했가**</ins> 계셨습니다.
- 저는 모르겠지만 (<ins>**^&^**</ins>) 추천합니다.
