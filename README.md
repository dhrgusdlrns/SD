이 페이지는에는 Stable Diffusion을 비롯한 AI 그림 생성 툴의 사용법과 관련한 것들을 방향성없이 아무 생각없이 적고 있습니다.

존나 쉬운 말과 최소한의 문장으로 이해하기 쉽게 정리하는 것을 목표로 삼고 있습니다.
그러나 다루는 내용 자체는 새로 나오는 기술과 그 사용법과 활용법을 다루고 있기에 기초적인 내용은 알아서 습득하시기 바랍니다.

SD (Stable Diffusion)

AI가 그림 만들어주는 기술입니다. 
이에 대해 이런저런 전문적이고 다양한 추가설명을 많이 할 수 있지만, 그건 알아서 찾으시고, 메인페이지에는 나오는 모든 기술이나 개념에 대해서는 딱 위와 같은 정도로 간단히 설명하겠습니다.

[기초] (https://github.com/dhrgusdlrns/SD/wiki/%EA%B8%B0%EC%B4%88)

AI 기술, Stable diffusion의 사용과 그 기초에 담고있는 페이지, 유용한 링크와 다른 사람들이 쓴 유용한 글들의 링크가 존재.


[설치](https://github.com/dhrgusdlrns/SD/wiki/%EC%84%A4%EC%B9%98):


WEB UI - SD 기술을 사람들이 편리하게 쓸 수 있게 해주는 프로그램. 현재 기준으로 대표적인 개발자는 Automatic1111

로컬 설치
1. SD는 컴퓨터 사양, 특히 그래픽카드의 사양을 엄청나게 많이 탑니다. 
장점: 

코랩 사용




기본 사용법은 알아서 

Text to Image
여기에 내용을 적으면 AI가 열심히 그림을 만들어 줍니다.

Prompt



테크닉


SD의 근본이 되는 기술은 사람이 글을 쓰면, 그에 맞는 그림을 그려주는 것이 기본이지만 매우 다양하게 활용할 수 있습니다.







Extentions (확장기능)






LORA

LORA 사용 관련된 코랩 링크

1.kohya-LoRA-dreambooth

https://colab.research.google.com/github/Linaqruf/kohya-trainer/blob/main/kohya-LoRA-dreambooth.ipynb#scrollTo=FKBrTDPrcNjP

2. 

3. 

4. 



파일 관리
1. 파일의 이름은 영향을 결과물에 영향을 미치지 않기 때문에, 다음과 같이 파일의 정보를 포함하고 있는 형태로 파일의 이름을 설정하는 것이 좋습니다. 
예시) (대상)_(토큰 키워드)_(기타 정보).safetensors -> 티모_Teemo_01.safetensors

2. 최신버전 WEBUI를 기준으로 LORA 모델을 저장하는 폴더 안의 폴더에 저장해도 정상적으로 불러올 수 있습니다. 파일이 많아지는 경우 분류해서 저장하는 것이 좋습니다.

사용 Tip
1. 웹 UI등 프롬프트 내에서 <lora:teemo:1>와 같이 불러오는 경우 해당 태그의 위치는 그림에 영향을 주지 않습니다. 맨 앞에 놓으나 맨 뒤에 놓으나 동일한 결과를 출력합니다.
단, 해당 키워드가 다른 키워드와 병합되어서 다른 태그의 위치에 영향을 주는 경우 결과물에 영향을 미칩니다.
예시) 
1. (같음) teemo, bad quality <lora:teemo:1> = <lora:teemo:1> teemo, bad quality 
2. (다름) teemo, bad quality <lora:teemo:1> != teemo, bad quality, <lora:teemo:1>

Automatic1111 WEB UI

확장 프로그램 업데이트
Check for updates를 누르면 업데이트 됩니다. 설치한 확장 프로그램이 많거나 용량이 큰 경우 오류가 종종 발생하나 계속 누르다보면 언젠가는 모든 확장프로그램의 업데이트가 완료됩니다.


