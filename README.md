# Visualization-of-topics-by-MBTI: 상위 10개의 MBTI topic을 추출하여 시각화

https://www.canva.com/design/DAGJ9hGLN9I/J1b-qqpsMQax3oD0ZdF8Ww/edit?utm_content=DAGJ9hGLN9I&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

설명: 해당 모델은 전처리 후 정리된 파일을 사용했으므로 각 프로젝트의 특성에 맞게 수정이 필요함. 

사용 데이터 : credit card fraud transaction dataset (Kaggle)

실습 환경: Google Colab notebooks

학습 언어: Python3

사용모델 : 

1. 토픽 모델링

잠재 디리클레 할당 (Latent Dirichlet Allocation, LDA): 텍스트 데이터에서 주제를 추출하는 데 사용되는 확률적 토픽 모델
관련 코드: lda.components_, lda.n_components
일반적으로 사용되는 라이브러리: gensim, scikit-learn


2. 텍스트 벡터화

TF-IDF (Term Frequency-Inverse Document Frequency): 단어의 중요도를 계산하여 텍스트를 벡터로 변환하는 방법
관련 코드: vectorizer.get_feature_names_out()
일반적으로 사용되는 라이브러리: scikit-learn

CountVectorizer: 텍스트에서 단어의 출현 빈도를 계산하여 텍스트를 벡터로 변환하는 방법
일반적으로 사용되는 라이브러리: scikit-learn

3. 시각화

Seaborn: Matplotlib 기반의 데이터 시각화 라이브러리입니다. 히트맵 등 다양한 시각화 기능을 제공
관련 코드: sns.heatmap

Matplotlib: Python에서 가장 널리 사용되는 데이터 시각화 라이브러리. 그래프, 차트 등을 생성하는 데 사용
관련 코드: plt.figure, plt.title, plt.xlabel, plt.ylabel, plt.show

WordCloud: 텍스트 데이터에서 단어의 빈도를 기반으로 워드 클라우드를 생성하는 라이브러리
관련 코드: WordCloud, wc.generate

Koreanize-Matplotlib: Matplotlib에서 한글 폰트를 사용할 수 있도록 지원하는 라이브러리

