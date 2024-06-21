# OBQA_Llamion

[llamion 모델](https://huggingface.co/vaiv/GeM2-Llamion-14B-Base)   
[PEFT 수행한 모델](https://huggingface.co/kimbong/llamion-14B-Base-TrainLoRA)

![image](https://github.com/kimbongju02/OBQA_Llamion/assets/106128768/40bd4137-e73d-426e-8116-626c89e4e72c)
기존에 존재하는 OPQA(Open Book Question Answering)는 이미 존재하는 Database에서 question과 유사한 문장을 뽑아내는 Retiever가 존재   
우리는 Retriver의 역할을 우리가 입력한 context에서 question과 유사한 문장을 추출하여 Generate 모델인 llamion에 입력으로 주어 answer에 대한 성능을 높이고자 한다.
