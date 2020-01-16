# 척척약사란?
### -> 22000여개의 알약 정보를 담았고, 63개의 알약을 Mask-RCNN으로 영상인식하여 어떤 약인지 분류하는 반응형 웹 사이트입니다.

**1. Getting Started** <br>
  - 개인 로컬 PC에서 test해보는 방법
    - springboot 서버(8000)와 tornado 서버(5000), elasticsearch(9200) 서버가 동시에 켜져있어야합니다. <br>
    - 학습된 가중치파일(h5, json)은 thdtlcks369@gmail.com으로 메일 주시면 보내드리겠습니다 ^^<br>
    - cmd 콘솔에 pip install -r requirements.txt로 필요한 라이브러리를 설치해주세요.

**2. 개발기간 & 개발배경 & Insight** <br>
  * 개발기간 : _19.12.10 ~ 20.01.14_ <br>
  * 개발배경 : 의약품에 대한 정보가 필요할 때, 아주 간편하게 식별 검색과 이미지 검색 기능을 제공하는 웹사이트입니다. <br>
  * Insight : Mask-RCNN으로 사진이나 영상의 여러 알약을 동시에 인식할 수 있으므로, 컴퓨터 비전과 하드웨어 구축을 통하여 의약품 자동분류기를 제작할 수 있을것입니다.

**4. Architecture** <br>
  * Spring MVC Pattern
  * Tornado Web Framework
  * Pills_Mask_RCNN
  * Elasticsearch
  
**5. Skill Set** <br>
  * Front-end : Javascript, HTML, CSS, Bootstrap, Axios    
  * Back-end : SpringBoot,  Google Cloud Platform  
  * DB : ElasticSearch, Kibana (v7.1.1) 
  * DL server : Tornado, TensorFlow v1.15.0, Keras, Opencv-Python, Cython  
  * Labeling Tool : VGG Image Annotator
  * Data Source : 보건의료빅데이터개방시스템, 식약처
  * Environment : Eclipse (Maven), VS code, Jupyter Notebook, Colab 

** 6. 실행화면 ** <br>
    ![이미지검색2-1](https://user-images.githubusercontent.com/40975942/72503039-1eae5e00-387e-11ea-8725-9d134abb9a57.jpg)
    ![이미지검색2-2](https://user-images.githubusercontent.com/40975942/72503109-4a314880-387e-11ea-8474-b5f7dc0914d8.jpg)
    ![이미지검색2-3](https://user-images.githubusercontent.com/40975942/72503110-4a314880-387e-11ea-9100-7eac3fc124c9.jpg)
    ![이미지검색2-4](https://user-images.githubusercontent.com/40975942/72503111-4a314880-387e-11ea-8f39-8ff8b94265e0.jpg)
    ![텍스트검색1-1](https://user-images.githubusercontent.com/40975942/72503112-4ac9df00-387e-11ea-881b-a693ed2dc68b.jpg)
    ![텍스트검색1-2](https://user-images.githubusercontent.com/40975942/72503108-4a314880-387e-11ea-8047-2aff51962c48.jpg)
    ![텍스트검색1-3](https://user-images.githubusercontent.com/40975942/72503175-7947ba00-387e-11ea-88fe-f2a6701962e7.jpg)
    ![텍스트검색1-4](https://user-images.githubusercontent.com/40975942/72503176-79e05080-387e-11ea-89cc-e92083a92f15.jpg)
    ![텍스트검색1-5](https://user-images.githubusercontent.com/40975942/72503178-79e05080-387e-11ea-8b67-bb2c8697e9d6.jpg)
    
    
