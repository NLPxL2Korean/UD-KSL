## advmod: Adverbial modifier

### Definition
`advmod` refers to an adverbial modifier that modifies a verb, an adjective, or another modifier.

---

### Characteristics
- From a part-of-speech perspective, advmod typically includes standalone adverb as well as verb or adjective that ends with the suffix '-게'.
- The advmod tag provides additional information regarding the manner, frequency, intensity, or degree of verbs, adjectives, and other sentence elements.
- **Examples**:
    - 한국어를 **매우** 잘하면 친구를 **쉽게** 만들 수 있습니다.
    - 수업을 **열심히** 들을수록 공부가 **재미있게** 느껴집니다.
    - 인터넷으로 그 장소를 **어떻게** 가는지 찾았다. 

---

### Boundary cases and clarifications

#### Differences with related tags
- **advmod vs. advcl (Adverbial clause modifier):**  
    - Both advmod and advcl can modify a verb or an adjective when combined with '-게', an EC (ending_connecting, 연결 어미). Unlike advmod, an element tagged as advcl can function as the main part of a clause.
    - When an adjective is combined with '-게', it is typically parsed as an advmod tag. In contrast, when a verb is combined with '-게', it is often parsed as an advcl tag, where preceding words can act as the subject or object of the clause.
        - 역사를 **배우게**(advcl) 되면 **새롭게**(advmod) 깨닫는 내용이 많다.
        - 한국어를 **자연스럽게**(advmod) 접하다보면 자기도 **모르게**(advcl) 익숙해집니다.

#### Special cases
- **Ungrammatical sentences element :**  
    - If a sentence element is an ungrammatical noun or appears to be a noun but its meaning cannot be clearly determined based on postpositions or context, it should be parsed as advmod and treated as dependent on the root. This ensures parsing consistency for elements with unclear meanings or functions.
        - 한국에 **저움** 가볼 계획이 있으세요?
        - 한국에 **저움** 가볼 계획이 있으세요?
        - 그 이야기는 **오후** **진짜** 슬픈 기분입니다.
          
---

### Examples
![advmod example](advmod.png)
