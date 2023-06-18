# 뀨뀨 크롤러(kkyukkyuCrawler)
> 강의안에서 판례요지 따기를 손쉽게!

뀨뀨 크롤러는 PDF 강의안의 판례번호(예: 1234다12345)를 자동으로 인식해서 [casenote](https://casenote.kr/)로부터 해당 판례를 검색한 후, 판례 정보를 긁어다가 txt 파일로 만들어주는 파이썬 라이브러리입니다.

판례를 찾아다니는 시간을 아껴 윤택한 로스쿨 생활을 해보아요!

## 설치
### 의존성
뀨뀨 크롤러의 요구사항은 다음과 같습니다:
- python (>=3.10)
- PyPDF2 (>=3.0.1)
- tqdm (>=4.65)
- beautifulsoup4 (>=4.12.2)

사실 파이썬3인 이상 버전은 조금 더 낮아도 될 것 같은데(시험해보지는 않음) 파이썬2는 안됩니다.

### 설치법
가장 쉬운 방법은 `pip`을 이용하는 방식입니다:

    pip install kkyukkyuCrawler

아니면 `git` repo를 클론해서 가져다 써도 됩니다:

    git clone ???

## 개발
뀨뀨 크롤러는 각잡고 영리목적으로 만든 게 아닙니다. 따라서 자잘한 버그가 있을수도 있고, 엉성한 부분이 있을수도 있습니다. 귀엽게 봐주시면 되겠습니다.

- 버그 리포트: lkd1962@naver.com

뀨뀨 크롤러는 MIT 라이선스로 자유롭게 활용이 가능합니다(영리목적도 가능). 이 라이브러리 코드를 기초로 뭔가 다른 걸 해보고 싶다면 얼마든지 환영입니다! 코드는 git repo에 있으니 