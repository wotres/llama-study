# Llama2

* 2조개의 학습 토큰 사용
* 70억 ~ 700억개의 매개변수 범위에 걸쳐 훈련 (7B ~ 70B)
* 모델 학습에 A100 331만 시간 동안 사용됨
* RLHF 사용

## RLHF 
* Reinforcement Learning from Human Feedback
* 인간의 피드백을 바탕으로 한 강화 학습
  * 안전성과 유용함

## 모델 다운로드
* 아래 주소에서 모델 이메일 요청 후 다운로드 (모델 가중치 다운)
  * https://ai.meta.com/llama/
* huggingface 에서도 동일하게 요청 후 다운로드
  * https://huggingface.co/meta-llama
  * huggingface 이용시 토큰 필요
    * https://huggingface.co/settings/tokens

## 파인튜닝
* 간단히 파인튜닝 도와주는 참고 패키지
  * https://github.com/huggingface/autotrain-advanced