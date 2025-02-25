## dislocated: Dislocated element

### Definition
`dislocated` refers to an element that is distinct from the main subject in a double subject construction.

---

### Characteristics
- In Korean, a single sentence can contain two subjects that correspond to one predicate, forming a 'double subject construction'. Typically, the first subject acts as a topic, while the second subject is directly related to the predicate. In this structure, the first subject is parsed as dislocated to distinguish it from the second subject.
- The dislocated tag is generally dependent on the root of the sentence.
    - **Examples**:
        - **코끼리가**(dislocated) **코가**(nsubj) 길다.  
        - **저는**(dislocated) **나이가**(nsubj) 많아요.

---

### Boundary cases and clarifications

#### Special cases
- **Parsing sentences that contain both a subject and a complement**:
    - In Korean, the case marker for complements, JKC (Postposition_complement, 보격 조사), is identical in form to the case marker for subjects, JKS (Postposition_nominative, 주격 조사). In the UD scheme, nominal complements are not classified as a separate category; instead, they are parsed as nsubj.
    - For example, in sentences that require a complement, such as those involving the predicates '되다' and '아니다', there are two ways to tag the subject, complement, and predicate: (1)**dislocated + nsubj + root**, (2)**nsubj + nsubj + root**
        - 그 **사람이**(dislocated/nsubj) **부자가**(nsubj) 되었다.  
        - **나는**(dislocated/nsubj) **학생이**(nsubj) 아니다.

---

### Examples
- <ins>**저는**</ins> 언니가 있어요.  
- <ins>**산은**</ins> 바람이 부니까 기분이 상쾌해요.  
- <ins>**여름이**</ins> 기온이 높고, <ins>**겨울이**</ins> 날씨가 춥다.  
- <ins>**친구가**</ins> 고민이 있어서 나한테 이야기를 했어요.  
- <ins>**사람들이**</ins> 나이가 어릴수록 언어를 더 쉽게 배운다.