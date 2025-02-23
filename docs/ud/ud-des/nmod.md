## nmod: nominal modifier

### Definition
`nmod` refers to a nominal modifier that specifies, qualifies, or describes a noun within a sentence.

---

### Characteristics
- The nmod tag typically appears before the noun it modifies and is syntactically dependent on that noun. The nmod tag provides additional information, such as attributes or specifications related to the modified noun.
- **Examples**:
    - 방학 전에 <ins>**여행**</ins> 계획을 세웠다.
    - <ins>**우리**</ins> 학교에 <ins>**학생**</ins> 식당이 있습니다.
    - <ins>**토요일**</ins> 아침에 출발하는 <ins>**비행기**</ins> 표를 예매했습니다.

---

### Boundary cases and clarifications
#### Differences from related tags
- **nmod vs. flat (Flat expression):**  
    - Both the nmod and flat tag refers to nouns in a sequence, but they differ in their syntactic relationship. When parsed as nmod, one noun modifies another, indicating a dependent relationship. In contrast, when parsed as flat, the nouns are in an equal, coordinate relationship.
        - 빌리 **씨는**(flat) **친구**(nmod) 카메라를 빌렸다.
        - 6월 **15일에**(flat) 출발하는 **여행사**(nmod) 상품을 신청했습니다.

---

### Examples
![nmod example](nmod.png)


## nmod:poss: Possessive modifier

### Definition
`nmod:poss` refers to a subtype of nominal modifier that emphasizes a possessive relationship between nouns.

---

### Characteristics
- The dependent noun tagged with nmod:poss modifies the head noun, specifying possession, ownership, or association.
- The nmod:poss tag is most commonly marked by JKG(Postposition_prenominal, 관형격 조사) such as '의'.
- The words '제' and '내' are contractions formed by combining the pronouns '저' and '나' with '의'. As a result, both '제' and '내' are parsed as nmod:poss.
- **Examples**:
    - 오늘은 <ins>**친구의**</ins> 생일입니다.
    - <ins>**한국의**</ins> 화장품 가게에서 일하고 싶어요.

---

### Examples
- 오늘은 <ins>**친구의**</ins> 생일이고, 이것은 <ins>**저의**</ins> 선물입니다.
- <ins>**한국의**</ins> 화장품 <ins>**가게의**</ins> 직원으로 일하고 싶어요.
- <ins>**제**</ins> 생각에 외국에서 공부하는 게 재밌어요.
- 친구를 만나면 <ins>**내**</ins> 기분이 좋아집니다.
