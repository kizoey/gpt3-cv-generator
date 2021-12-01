# gpt3-cv-generator
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/GoogleColab-F9AB00?style=flat-square&logo=GoogleColab&logoColor=white"/></a>&nbsp 
</p>
<b><i>CV Generator</i></b> is a service that automatically generates a piece of curriculum vitae by entering the first sentence or a few starting words. For instance, if you enter '저의 강점은 성실함입니다.' (One of the strengths is diligence.), the model will automatically generate more sentences that are related to the input sequence. This process is done by utilizing a powerful pre-trained generative language model <a href=https://github.com/openai/gpt-3><b>GPT-3</b></a>. GPT-3 predicts the next token by using the words of the previous tokens. 
<br>Also, in recent years, it became a trend to provide a one-line summary per each statement. To follow this trend, we also provide an extractive summarization of the generated statement based on <b>LexRank</b> algorithm. <br>
<br>
CV generator can be a powerful tool in 3 ways:

- Generates your own cv statements based on the accepted statements dataset.
- Provides inspirational text or keywords when writing statements.
- Acts as a self-branding tool that can be applied to various statements or portfolios.


<h2> major Contributions </h2>

- Fine-tune pre-trained model **GPT-3** with crawled dataset
- Generation of cv statements based on accepted statements dataset 
- Extractive summarization with **LexRank** algorithm
- Crawling accepted statements: <a href=https://linkareer.com/>Linkcareer</a> / <a href=https://www.jobkorea.co.kr/> JobKorea </a>
- Provision of self-branding tool for members of data science society 'KUBIG'

<h2> Directory </h2>

### _algorithms_
- **train**: 데이터 전처리, GPT3 fine-tuning
- **generate**: fine-tuning된 모델 불러와 자기소개서 생성


### _data_
- **preprocessed_data**: 잡코리아/링커리어에서 크롤링 후 전처리한 데이터 csv 파일

### _ppt_
- 1차 발표자료
- 2차 발표자료
- 최종 발표자료


<h2> Demo </h2>
<a href=https://colab.research.google.com/drive/1D5DCA-ulr_J_h6H12ZgcotHRfmIzSOBA?usp=sharing><b>Demo</b></a> is now released with Google Colab !
