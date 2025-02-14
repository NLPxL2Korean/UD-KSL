## XSA: Suffix_adjective_derivative (형용사 파생 접미사)

### Definition
XSA refers to a suffix that attaches to a noun or root to form an adjective stem.

---

### Characteristics
- XSA primarily attaches to a noun to indicate a characteristic related to the meaning of the preceding noun or to express a quality typically associated with the noun.
- **Examples**:
  - 저는 **피곤해서** 쉬고 싶어요: 
    - 피곤 (fatigue) → 피곤**하다** (to be tired)
  - 기분을 **자유롭게** 표현해보세요
    - 자유 (freedom) → 자유**롭다** (to be free)

---

### Boundary cases and clarifications

#### Differences with related tags
- **XSA vs. VA (adjective, 형용사):**
  - Adjectives formed with ‘noun + 있다/없다’ have a structure similar to ‘noun + XSA,’ but ‘있다/없다’ should be tagged as VA rather than XSA.
  - Since ‘있다/없다’ is listed as an adjective in dictionaries, cases where a noun combines with these words should be parsed as a compound word rather than a derived form.
    - 이 책은 **재미있다**: 재미(NNG) + 있(VA) + 다(EF)
    - 이 음식은 **맛없다**: 맛(NNG) + 없(VA) + 다(EF)

#### Special cases
- **Parsing approaches for XSA in different contexts:**
  - While XSA primarily attaches to nouns, it can also attach to roots or determiners to form a adjective. In such cases, there are two possible parsing approaches; (1)Separating XSA for parsing, (2)Not distinguishing XSA and parsing only the adjective stem.
    - (1) 가을 날씨가 **쌀쌀하다**: 쌀쌀(XR) + **하(XSA)** + 다(EF)
    - (2) 오늘 **새로운** 사람들을 만났습니다: 새롭(VA) + ㄴ(ETM)

---

### Examples
- 가을 날씨가 쌀쌀<ins>**하**</ins>다.
- 주말을 행복<ins>**하**</ins>게 보냈습니다.
- 비싸지만 유명<ins>**한**</ins> 식당에 갔습니다.
- 학생은 학생<ins>**답**</ins>게 열심히 공부해야지.
- 경제적으로 부담<ins>**스러운**</ins> 가격이네요.
