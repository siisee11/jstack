---
name: unslop
description: Cut AI tells from any writing. Must always apply.
---

# Unslop

Edit text to remove AI patterns and add human voice.

## Process

1. Scan for the patterns below.
2. Rewrite. Preserve meaning, match intended tone.
3. Add soul (see next section).
4. Self-audit: "What makes this obviously AI generated?" Fix remaining tells.

## Adding soul

Removing patterns is half the job. Sterile, voiceless writing is just as obvious.

- **Have opinions.** React to facts instead of neutrally listing pros and cons.
- **Vary rhythm.** Short sentences. Then longer ones that take their time. Mix it up.
- **Acknowledge complexity.** "Impressive but also kind of unsettling" beats "impressive."
- **Use "I" when it fits.** First person isn't unprofessional.
- **Let some mess in.** Perfect structure looks machine-made.
- **Be specific.** Not "this is concerning" but "there's something unsettling about agents churning away at 3am."

## Patterns to detect and fix

### Content

1. **Puffery.** "pivotal moment", "testament to", "evolving landscape", "setting the stage for", "indelible mark", "deeply rooted". Cut puffery, state what happened.
2. **Name-dropping.** Listing media outlets without context. Pick one, say what was said.
3. **Superficial -ing phrases.** "highlighting...", "ensuring...", "reflecting...", "showcasing...", "fostering...". Delete or expand with real sources.
4. **Promotional language.** "nestled", "vibrant", "breathtaking", "groundbreaking", "renowned", "stunning", "must-visit". Use neutral descriptions.
5. **Vague attributions.** "Experts believe", "Industry reports suggest", "Some critics argue". Name the source or delete.
6. **Formulaic challenges.** "Despite challenges... continues to thrive." Replace with specific facts.

### Language

7. **AI vocabulary.** Additionally, crucial, delve, enduring, enhance, fostering, garner, interplay, intricate, landscape (abstract), pivotal, showcase, tapestry (abstract), testament, underscore, vibrant. Replace with plain words.

   한국어 요청에서는 다음 한국어 AI 어휘와 번역투도 점검한다. 아래 표현을 금지하지는 않지만, 반복되거나 구체적인 뜻 없이 쓰였으면 줄인다.

   - "또한", "나아가", "궁극적으로", "유의미한", "효과적으로", "다양한", "복합적인", "유기적인", "지속적으로", "이를 통해"
   - "~에 대해(서)" 남발 → 목적격 조사로 직결. "X에 대해 논의" → "X를 논의"
   - "~를 통해/통하여" 반복 → "~로", "~해서", "~함으로써"로 분산
   - "~에 있어(서)" → "~에서" 또는 "~을 볼 때"
   - "~라는 점에서" 반복 → "~라서", "~라는 이유로"
   - "~와 관련하여/관련된" → "~에", "~의"
   - "~에 기반하여/바탕으로" → "~로", "~을 보고"
   - "가지고 있다" → "~이다", "~하다", "~이 강하다"
   - "~을 위해" 반복 → "~하려고", "~하도록", "~을 위한"
   - 영어 원문을 한국어로 옮길 때 "그", "그녀", "그것", "그들"이 반복되면 생략하거나 명사로 바꾼다. 원래 한국어 글에는 기계적으로 적용하지 않는다.

8. **Fancy ways to say "is".** "serves as", "stands as", "boasts", "features". Just say "is" or "has".

   한국어에서는 단순히 "~이다", "~있다", "~한다"라고 하면 되는 곳에서 "역할을 한다", "자리매김한다", "선보인다", "보유하고 있다", "특징으로 한다", "제공한다"를 쓰지 않는다. 실제 행동을 설명할 때만 해당 동사를 쓴다. "기술이 묻는다", "시대가 요구한다"처럼 추상 주어가 행동하는 표현도 구체적인 사람, 조직, 기능으로 바꾼다.

9. **"Not just X, but Y."** State the point directly instead.

   한국어에서도 "단순히 X를 넘어 Y", "A인가 B인가", "X뿐 아니라 Y도" 같은 대구를 반복하지 않는다. 실제 대비가 필요할 때 한 번만 쓰고 나머지는 직접 단언한다.

10. **Rule of three.** Forcing ideas into groups of three. Use the natural number.

   한국어에서 "크게 세 가지로 나눌 수 있다", "첫째, 둘째, 셋째"를 내용상 필요할 때만 쓴다. 실제 항목 수와 자연스러운 순서를 따른다.

11. **Synonym cycling.** Protagonist, main character, central figure, hero all in one paragraph. Pick one, repeat it.

   한국어에서도 같은 대상을 문단 안에서 여러 이름으로 부르지 않는다. "주인공", "중심인물", "핵심 인물", "영웅" 중 하나를 고르고 반복한다.

12. **False ranges.** "from X to Y" where X and Y aren't on a meaningful scale. List topics directly.

   한국어에서 실제 척도가 아닌데 "~부터 ~까지"라고 쓰지 않는다. 주제를 직접 나열한다.

### Style

13. **Em dash overuse.** Avoid em dashes entirely. Use periods or commas only (no parentheses, no en dashes, no hyphen-as-dash substitutes). Em dashes are an AI tell, and reaching for parentheses instead just trades one tell for another. If a thought needs separation, end the sentence or use a comma.
14. **Colon overuse.** Colons are fine before a list or example. Not as mid-sentence connectors. "If you're coming from traditional automation: instead of registering event handlers, you describe conditions" adds nothing with the colon. Rewrite to let the point stand on its own without comparison framing. "Describing when the scheduler should fire works best as plain English." Same meaning, no crutch punctuation.
15. **Boldface overuse.** Don't bold every proper noun or acronym.
16. **Inline-header lists.** The tell is a bold label and colon that restates the line: "**Performance:** Performance improved...". Convert those to prose. A bold lead-in that ends in a period, names the item, and is followed by genuinely new detail ("**Schema in TypeScript.** Tables live in one file.") is fine, not a tell.

   한국어의 "**성능:** 성능이 향상되었다" 같은 인라인 헤더도 같은 기준으로 일반 문장으로 합친다.

17. **Title case headings.** Use sentence case.

   한국어 헤딩은 문장형이나 짧은 명사구로 쓴다. 모든 단어를 같은 방식으로 꾸미거나 콜론 부제를 반복하지 않는다.

18. **Decorative emojis.** Remove from headings and bullets.
19. **Curly quotes.** Replace with straight quotes.

   한국어 글에서는 직접 인용, 용어 정의, 제목처럼 필요한 따옴표만 남긴다. 강조용 따옴표는 평어로 풀고 표기를 통일한다.
   한글 용어 뒤의 영어 괄호 병기는 첫 등장에만 한다. 표준 기술 용어는 통용 표기를 유지한다.

### Communication artifacts

20. **Chatbot phrases.** "I hope this helps!", "Let me know if...", "Of course!", "Certainly!", "Found the smoking gun!" Remove.

   한국어에서는 "도움이 되었길 바랍니다", "궁금한 점이 있으면 알려주세요", "물론입니다", "좋은 질문입니다", "정확한 지적입니다", "잘 짚으셨습니다", "제가 도와드리겠습니다", "함께 살펴보겠습니다" 같은 표현은 문맥상 꼭 필요하지 않으면 삭제한다.

21. **Cutoff disclaimers.** "While specific details are limited..." Find sources or remove.

   한국어에서는 "구체적인 정보는 제한적이지만", "현재 공개된 정보만으로는", "자세한 내용은 알 수 없지만" 같은 문장을 습관적으로 쓰지 않는다. 실제로 중요한 제한이라면 무엇이 부족한지 구체적으로 쓴다.

22. **Sycophantic tone.** "Great question! You're absolutely right!" Respond directly.

   한국어에서는 "정말 좋은 의견입니다", "전적으로 동의합니다", "훌륭한 질문입니다"처럼 사용자에게 아첨하지 않는다. 바로 내용으로 들어간다.

### Filler

23. **Filler phrases.** "In order to" becomes "To". "Due to the fact that" becomes "Because". "It is important to note that" gets deleted.

   한국어에서는 "~하기 위해서"를 "~하려고"나 "~하도록"으로 줄인다. "이러한 맥락에서", "무엇보다", "다시 말해", "살펴보면", "결론적으로", "한편" 같은 접속어는 흐름에 필요할 때만 남긴다.

24. **Excessive hedging.** "could potentially possibly be argued that it might" becomes "may".

   한국어에서는 "~할 가능성이 있을 수 있다", "~로 보여질 수 있다", "~라고 볼 수 있을지도 모른다"처럼 완곡 표현을 겹치지 않는다. 실제 추측과 유보는 유지하되 완곡 표현 하나만 남긴다.

25. **Generic conclusions.** "The future looks bright." State specific plans or facts.

   한국어의 "미래는 밝다", "새로운 가능성을 열 것이다", "앞으로도 기대된다", "귀추가 주목된다", "지속적인 관심이 필요하다" 같은 결론은 구체적인 계획, 결과, 조건으로 바꾼다.

### Jargon

26. **Abstract metaphor nouns.** Substrate, wedge, vector, locus, vantage, nexus, primitive (as noun), harness (as metaphor), surface (as in "API surface"), bedrock, scaffolding (as metaphor), modality, paradigm, gold-plating, ratchet (as metaphor), evacuate (for moving code), endgame, north star, flywheel. These read as technical but usually have a plainer concrete word. "Substrate" becomes "base". "Wedge in" becomes "add". "Vector" becomes "way" or "method". "Gold-plating" becomes "more than the job needs". "Ratchet" becomes the mechanism's real name or "a limit that only tightens". "Evacuate" becomes "move out". "Endgame" becomes "the last phase". Pick the concrete word.

   한국어에서도 "생태계", "지형", "패러다임", "프레임워크", "접점", "축", "동력", "지렛대", "촉매", "발판", "청사진", "로드맵", "여정", "서사", "레버리지", "북극성", "플라이휠"을 정확한 기술적 의미 없이 쓰지 않는다. 비유라면 기능, 방법, 범위, 원인, 목표처럼 구체적인 말로 바꾼다.

### Plain speech

27. **Say what it does, not how it feels.** "the database stays close at hand", "SQL you can read", "types that follow your schema" name a feeling. The fix names the mechanism or a number: "`.toSQL()` returns the exact string sent to the database", "a column rename fails the build". Ask what the sentence tells the reader to do or know, then write that. If you can't restate it as a concrete instruction, fact, or number, cut it. One more check: if the sentence could appear unchanged in another project's docs, it says nothing about this one. Cut it.
28. **Shorten or split dense sentences.** If the reader has to backtrack to parse a sentence, break it in two or drop clauses. One idea per sentence.

   한국어에서는 명사 앞에 긴 관형절이 이어지면 문장을 나누거나 뒤에서 설명한다. "~에서의", "~으로부터의", "~에로의" 같은 이중 조사는 절이나 구로 풀어쓴다.

29. **Active voice.** Prefer it. Catch "is/are/was/were + past participle" and name the actor: "queries are validated" becomes "the compiler validates queries", "the file is parsed by the loader" becomes "the loader parses the file". Passive is fine only when the actor is unknown or genuinely doesn't matter.

   한국어에서는 "~되어진다", "~지게 된다", "~에 의해" 같은 피동 표현을 가능한 한 행위자를 주어로 하는 능동문으로 바꾼다. "AI에 의해 생성된"은 "AI가 만든"으로 쓴다.

30. **Cut adverbs, or use a stronger verb.** "runs quickly" becomes "is fast" or the number. "significantly improves" becomes the measured delta. An adverb propping up a weak verb means the verb is wrong.
31. **Prefer the plain word.** "utilize" becomes "use", "leverage" becomes "use", "facilitate" becomes "help", "numerous" becomes "many", "in the event that" becomes "if". The fancier synonym is rarely clearer.

   한국어에서는 "활용하다"를 "사용하다", "도모하다"를 "돕다"나 실제 행동, "제고하다"를 "높이다", "수행하다"를 "하다", "다수의"를 "많은", "~하는 경우"를 "~하면"으로 바꾼다. 다만 문서의 장르와 격식에 맞는 표현은 보존한다.
