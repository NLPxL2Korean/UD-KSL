## JKQ: Postposition_quotative (인용격 조사)

### Definition
JKQ refers to a postposition that indicates quoted speech, thoughts, or references in a sentence.

---

### Characteristics
- Quotations are classified into two types: direct and indirect.
- The main JKQ for direct quotations is ‘(이)라고’, where ‘이라고’ follows a final consonant, and ‘라고’ follows a vowel.
- Indirect quotations use ‘고’, but JKQ is not separated during parsing. For example, ‘다고’ is a fixed form that combines ‘-다’ (an ending marker, EC) with ‘고’. In expressions like ‘-다고’ or ‘-냐고’, the function as an ending is stronger than JKQ, so they are generally tagged as EC.
- **Examples**:
    - "괜찮아"**라고(JKQ)** 말했습니다. (Direct quotation)
    - 괜찮**다고(EC)** 말했습니다. (Indirect quotation)

---

###Boundary cases and clarifications

#### Special cases
1. **Use of '하고' as a quotative postposition**
    - Although '하고' originates from the verb '하다', it has been lexicalized as a quotative expression similar to '라고' and is therefore tagged as an JKQ.
        - "사진기를 빌려 주세요" **하고/라고(JKQ)** 부탁했습니다.

2. **Contracttion of quotative expressions**
    - Certain expressions, such as '-(이)라는,' are contracted forms of longer quotative constructions. '(이)라는' originates from '(이)라고 하는,' where '-는' serves as ETM (Ending_determinitive, 관형사형 전성 어미). Since these contracted forms are not typically separated into their original components during parsing, distinguishing between ETM and JKQ can sometimes be unclear.
        - 내 좋아하는 사람은 철수**라는(JKQ/ETM)** 친구입니다.
        - 친구는 나에게 "수박"**이라는(JKQ/ETM)** 별명을 붙여주었다.

---

### Examples
- "사진기를 빌려 주세요" <ins>**하고**</ins> 부탁했습니다.
- 한국에서 온 철수<ins>**라고**</ins> 합니다.
- 이번이 벌써 5번째 여행이<ins>**라고**</ins> 한다.
- "그냥 도움을 주고 싶었다"<ins>**라는**</ins> 대사가 기억에 남는다.
- 친구는 나에게 "수박"<ins>**이라는**</ins> 별명을 붙여주었다.
