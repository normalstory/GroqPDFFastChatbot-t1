### Groq 첫번째 실습 ###

**1. GroqChat sign-up, key발급** 
    
    GroqCloud(https://console.groq.com/keys)


**2. 가상환경 설정( *`groq-t1` 는 본인이 만들고자하는 임의의 이름)**

    `python -m venv groq-t1`


**3. 가상환경 실행** 

    맥 : `source groq-t1/bin/activate`   

    윈도우 : `groq-t1\bin\activate`

    종료(동일) : `deactivate`)


**4. 필요한 LB 설치(의존성 DI Dependency Injection 관리)**

    `pip install -r requirements.txt`


**5. ollama에 모델 추가** 

    `ollama pull nomic-embed-text`


**6. 실행하기** 

    `chainlit run [app.py](http://app.py/)`
    

**7. 접속하기**

    [http://localhost:8000](http://localhost:8000/)


**8. 사용하기**
* 질의 내용과 결과
> <img width="600" alt="image" src="https://github.com/normalstory/GroqPDFFastChatbot-t1/blob/main/result/r2.png/">
* 업로드 원문의 일부
> <img width="600" alt="image" src="https://github.com/normalstory/GroqPDFFastChatbot-t1/blob/main/result/r1.png">

* 튜토리얼 출처
    www.linkedin.com/in/stevado 
