# SD


LORA

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





이 페이지는에는 
이것저것 많이 모읍니다.
