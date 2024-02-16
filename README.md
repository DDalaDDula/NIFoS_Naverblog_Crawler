# Naver Blog Crawler
데이터 디렉토리 생성부터 데이터 저장까지 자동화된 네이버 블로그 크롤러

원하는 기간을 설정하고 키워드를 설정하면 일정 기간 내의 키워드를 포함한 블로그 포스트를 전부 크롤링합니다.

차단을 피하기 위해 time.sleep() 을 충분히 걸었기 때문에, 데이터 수집 기간이 꽤 걸립니다.

func.py파일의 22번째 라인에 있는 크롬 드라이버 경로를 알맞게 수정하여 사용하면 됩니다.
### Set up

    git clone git@github.com:DDalaDDula/NIFoS_Textdata_Analysis.git
    cd NIFoS_Textdata_Analysis

---
### Environment

    conda env create -f NIFOS.yaml   -- 가상환경이 activate 되어있을 때
    conda activate NIFOS

