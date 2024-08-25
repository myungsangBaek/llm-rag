### RAG를 활용한 APP 개발

```bash
# Notebook 실행 방법 shift + enter

# 만약 환경변수에서 추상화된 API KEY NAME(OPENAI_API_KEY) 말고 다른 이름을 사용하고 싶을 경우
import os
api_key = os.getenv('API_NAME')
llm = ChatOpenAI(api_key=api_key)
```

LangChain에 Chat Model만 바꿔주면 다른 model을 쉽게 연동할 수 있다.
