## LLM
LLM(Large Language Model)은 사용자의 질문에 대답을 제공하거나, 언어적인 작업을 수행하는 데 유형이며 자연어 입력을 할 시 인간과 유사한 답변을 생성하여 대규모 테스트 셋에서 훈련된 인공 진으 유형을 말합니다.

## Langchain
개발자가 End to End Application을 구축할 수 있도록 설계한 프레임워크입니다 모듈식 빌딩 블록을 두고, 프롬프트 템플릿, 언어 모델, 출력 파서가 포함된 체인과 함께 작동하여 사용자 입력을 처리하고 응답을 생성하고 출력을 처리합니다. 주로 채팅 인터페이스를 통해 언어 모델과 상호작용하며 이전의 모든 채팅 상호 작용을 기억하고 이를 다시 모델에 전달해서 다른 방식으로 결합할 수 있습니다.

## 프롬프트 템플릿
언어 모델에 최종적으로 전달하는 프롬프트 값을 생성하는 역할입니다.

## 출력 파서
언어 모델 답변을 쉬운 형식으로 구조화하는 작업을 담당하는 역할입니다.
형식 지정을 정한 후 제공하는 방법
언어모델의 답변을 구조화된 형식으로 구문 분석하는 방법
## chain
출력 파서, 프롬프트 템플릿, 에이전트를 모두 잇는 역할