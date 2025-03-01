## obl: Oblique nominal

### Definition
`obl` refers to a nominal adverb that functions as a sentence component modifying the predicate.

---

### Characteristics
- The obl tag is typically composed of noun + JKB (Postposition_adverbial, 부사격 조사), such as '에게', '에서', '한테', '에', '(으)로', and '께'.
- The obl tag provides additional information about direction, time, location, manner, or cause.
- **Examples**:
    - 나는 **부산으로** 여행을 가요.
    - **1시에** 미팅이 있습니다.
    - 우리는 바다 **근처**에서 식사를 했습니다.
    - 비행기가 비싸서 **기차로** 이동합니다.

---

### Boundary cases and clarifications
#### Differences with related tags
- **obl vs. advmod (Adverbial modifier):**  
    - Both the obl and advmod tags function as adverbials within a sentence. From a part-of-speech perspective, the obl tag generally includes a noun, whereas the advmod tag typically consists of either adverbs or verb stems combined with the suffix '-게'.
    - Some Korean words such as '어제' and '오늘' can function as both nouns and adverbs, allowing for both obl and advmod tagging depending on the context.
        - **obl**: **기차로** 이동합니다.
        - **advmod**: **천천히** 이동합니다.

- **obl vs. conj (Conjunct):**  
    - Some JKBs (Postposition_adverbial, 부사격 조사) share the same surface form as certain JCs (Postposition_conjunctive, 접속 조사), such as ‘와/과’, ‘하고’, and ‘(이)랑’. When functioning as JKBs, they are parsed with the obl tag, whereas when functioning as JCs, they are related to the conj tag.
    - The obl is used when the phrase modifies or specifies the predicate, while the conj indicates an equal relationship between two words or phrases in the sentence.
    - The obl tag is generally dependent on the root of the sentence or clause, while the conj tag is dependent on a preceding word that it connects to as an equal.
        - **obl**: **친구하고** **커피숍에** 왔습니다.
        - **conj**: 식당하고 **커피숍이** 명동에 많습니다.

#### Special cases
- **Nouns accompanied by prepositional words:**  
    - When a noun is used with a word that functions like a preposition, it is typically tagged as obl. Common examples in Korean include '앞'(in front of), '옆'(beside), '뒤'(behind), '전'(before), and '후'(after).
        - **학교** 앞에서 친구를 기다린다.
        - **학교** 앞에서 친구를 기다린다.
        - 식사를 **마치기** 전에는 먼저 일어나면 안 됩니다.

---

### Examples
![obl Example](obl.png)
