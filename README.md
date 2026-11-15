# HOPPER: Context Compression for Small Language Models

> **Status:** accepted at IJIBC (International Journal of Internet, Broadcasting and Communication); publication scheduled for December 2026. Code will be released with the publication (공개 예정).

HOPPER (Header-preserving One-Pass Pseudo-relevance Extraction for small Readers) is a training-free sentence extraction method that compresses long retrieved documents for small language models (1B–4B parameters) in multi-hop question answering. It ranks sentences with BM25, expands the query once with capitalized and title words of the top-ranked sentences, and keeps the document title line of every selected sentence within the token budget. No language model or trained model is run at compression time.

This repository accompanies the paper "HOPPER: Context Compression for Improving the Accuracy of Small Language Models in Long Multi-Hop Question Answering" (IJIBC, accepted).

**The code will be added with the publication.** It will include the compression code, prompts, evaluation question IDs, model digests and run records.

Follow-up: [HOPPER-G](https://github.com/sungchul02/HOPPER-G) (in progress).

---

HOPPER는 긴 멀티 홉 질의응답에서 소형 언어모델(10억∼40억 파라미터)을 위해 검색 문서를 압축하는 문장 추출 방법이며, 학습이 필요 없다. 논문은 IJIBC에 게재가 확정되었고 2026년 12월에 게재될 예정이다. **코드는 게재 시 이 저장소에 기재한다**(압축 코드, 프롬프트, 평가 질문 ID, 모델 식별 해시값, 실행 기록). 후속 연구는 [HOPPER-G](https://github.com/sungchul02/HOPPER-G)이다.
