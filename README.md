# OSS-
import pandas as pd
os.chdir(path)
# 여기서 캐글에서 데이터폴더를 보니 netfilx_titles.csv폴더 하나밖에 없었으므로 저걸 바로 데이터프레임으로 만들고 불러왔다.
df = pd.read_csv('netflix_titles.csv')

df.head(10)
