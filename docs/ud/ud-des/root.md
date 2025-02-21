## root: Root of the sentence

### Definition
`root` refers to the core syntactic head of a sentence, typically a predicate such as a verb or adjective that describes the subject’s action, state, or quality.

---

### Characteristics
- The root tag represents an essential component of a sentence. It is generally found at the end of a sentence in the form of a verb, adjective, or copula combined with EF (Ending_Closing, 종결 어미).
- The root tag is the central element to which all other words in the sentence connect, either directly or indirectly. When there is ambiguity regarding the syntactic dependency of a sentence component, the default principle is to make it dependent on the root.
- **Examples**:
  - 나는 점심을 맛있게 <ins>**먹었다**</ins>.
  - 나와 친구는 모두 집으로 돌아갈 <ins>**겁니다**</ins>.
  - 산에 가서 사진을 많이 <ins>**찍으세요**</ins>.
  - 바람이 부니까 기분이 <ins>**어때요**</ins>?

---

### Boundary cases and clarifications

#### Special cases
1. **Coordinated clauses**
  - When two or more clauses within a sentence are connected in a sequential, contrasting, or alternative relationship, the first predicate is parsed as the root, while the others are tagged as conj (Conjunct) dependent on the root.
  - If conj is dependent on the root, the coordinating relationship is typically expressed using EC (Ending_Connecting, 연결 어미) such as '-고', '-(으)며', or '-(으)나'.
    - 방학 때 수영을 <ins>**했고**</ins>(root) 말도 <ins>**탔습니다요**</ins>(conj).
    - 사진을 <ins>**찍거나**</ins>(root) 꽃을 <ins>**구경해요**</ins>(conj).

2. **Copular constructions with '이다'**
  - '이다' is the representative VCP (Copular_Positive, 긍정 지정사). Unlike general lexical verbs, VCP does not carry an independent meaning. Therefore, it must be attached to the preceding word to form a grammatically and semantically correct phrase.
  - However, non-standard sentences often separate '이다' from the preceding word. In such cases, the word preceding '이다' is parsed as the root, while '이다' is tagged as case(Case marker) that designates the root.
    - 8월은 무더운 <ins>**여름**</ins>(root) <ins>**입니다**</ins>(case).
    - 주장에 대한 근거는 세 <ins>**가지**</ins>(root) <ins>**이다**</ins>(case).

---

### Examples
![root example](root.png)