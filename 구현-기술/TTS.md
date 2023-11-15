# TTS
Text To Speech

텍스트를 음성으로 바꿔서 말해주는 서비스

- [네이버](https://www.ncloud.com/product/aiService/clovaVoice)
- [카카오](https://kakaocloud.com/service/detail/6-34)
- [구글](https://cloud.google.com/text-to-speech?hl=ko)
- [타입캐스트](https://typecast.ai/)

국내 기업들의 TTS가 다양한 목소리의 형태로 지원해주어서 더 듣기 편하고 자연스럽지만, 클라우드에 가입해야하고 가격이 비쌈

[구글TTS 가격](https://cloud.google.com/text-to-speech/pricing?hl=ko)은 월마다 1백만자가 무료로 할당해줘서 거의 무료로 사용 가능 (자신 목소리 입력으로 학습도 가능해서 나중에 잘 사용하면 좋을것같음)

타입캐스트는 성우도 많고 자연스러움. 무료플랜은 한달에 3분이지만, 잘 이용하면 프로젝트 시연 영상 찍을때만 사용하기 적당할 수 있음

테스트는 구글것으로 하기

# 실시간 TTS
실시간으로 텍스트를 음성으로 바꿔주는 기술

현재 있는 대부분의 TTS는 여러개의 단위, 문장을 한번에 번역하는것을 전제로 하고 있지만, 실시간으로 들어오는 텍스트에 대해서 음성을 만드는 것은 또 다른 일.

- [gemelo](https://gemelo.ai/): 실시간 TTS 스트리밍 스타트업 (영어만 가능)
- [docs](https://www.notion.so/TTS-02db7a4c139444c382d6400c4bb52e81?pvs=21): api docs

오픈소스 [PaddleSpeech](https://github.com/PaddlePaddle/PaddleSpeech)도 사용가능 (영어, 중국만 가능)

# 크롬 내장 TTS 엔진
라이브러리 없이 내장되어있는 TTS엔진으로 음성합성 가능. 하지만 지원하는 언어가 많지 않고, 목소리의 화자가 제한적