# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 강상현
- 리뷰어 : 손정희


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
```
제출되었습니다.
# 입력 받아서 정수 리턴 함수

def text_index():
  lst = input("텍스트를 입력하세요.")
  lst = lst.lower()
  lst = re.sub(r"[^a-z\s]","",lst)
  tokens = lst.split()

  result = []
  for token in tokens:
    if token in word_to_index:
      result.append(word_to_index[token])
  return result


text_index()

```

    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
```
이해하는데 어려움이 없었습니다. 
```
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [x]  **4. 회고를 잘 작성했나요?**
```
전체적으로 잘 작성되었습니다.

```
        
- [x]  **5. 코드가 간결하고 효율적인가요?**
```
정규화 코드를 통해 간소화 된것으로 보입니다.
#모든 기호 제거(숫자 포함)
data = re.sub(r"[^a-z\s]","",data) #(패턴, 바꿀 문자열, 원본 문자열 )
```


# 회고(참고 링크 및 코드 개선)
```
정규식을 통해서 코드를 간소화 하여 좋았습니다. 
```
