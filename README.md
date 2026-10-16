# LLM 평가 지표 딥다이브

본 저장소는 LLM 답변의 rubric을 연구를 위해 작성되었습니다.

LLM as a judge과 golden set 도입 시 개선사항
- 평가 항목이 주관적인 경우에는 검수자의 주견에 따라 의견이 달랐습니다.
- 답변의 일관성은 Text2SQL 적용 시에 데이터 또는 원장(ledger)의 복잡도와 상관없이 RAG가 해결되면 정확도는 높았습니다.
- 랜덤한 답변을 줄 수 밖에 없는 경우에는 실무자를 위주로 맞춤화하는 것이 옳은 방향성인지에 대해서는 충분한 토론이 필요합니다.
- 싱글턴과 멀티턴 모두 평가를 자동화 할 수 있었습니다.(적용하지 않음)
- 평가 기준이 휴먼 에러 또는 집단의 확증편향에서 자유로운지 검토해야 됩니다.
- 현업과 실무에서의 rubric이 주관적이기에 지표마다 정책과 거버넌스가 필요하다고 판단했습니다.
  a. 해결하지 못한 문제점: A or B 또는 1부터 5까지의 숫자로 평가한다고 할 때, 사용자가 느끼는 평가와 평가자가 느끼는 평가는 차이가 크다. 사용자의 평가에 가중치를 두는 방법도 있으나 그만큼 사용자가 많거나, 운영 기간에 대한 정책도 마련해야됨.
- Metric을 지속적으로 관리하면 됩니다.

# TOC

1. 찾아본 자료
2. 수치 검증
3. 결론

## 1. 찾아본 자료 

[Google Stax](https://stax.withgoogle.com/landing/)
[LLM as a Judge](https://arxiv.org/abs/2411.15594)
[LLM evaluation Guidebook](https://huggingface.co/spaces/OpenEvals/evaluation-guidebook#what-is-model-evaluation-about)
[Quantifying Biases in LLM-as-a-Judge](https://arxiv.org/abs/2410.02736)
[TurnWise](https://arxiv.org/html/2603.16759v1)

논문 리뷰는 Notion에 작성하였습니다.

## 2. 수치 검증

Notion에 작성하였습니다.

## 3. 결론

> Metric을 지속 관리하고 품질을 유지한다.

Notion에 작성하였습니다.
