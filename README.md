# From collecting text data To analyzing
데이터 디렉토리 생성부터 데이터 저장까지 자동화된 네이버 블로그 크롤러

원하는 기간을 설정하고 키워드를 설정하면 일정 기간 내의 키워드를 포함한 블로그 포스트를 전부 크롤링합니다.

차단을 피하기 위해 time.sleep() 을 충분히 걸었습니다. 링크를 먼저 긁어오고 본문을 긁어오기 때문에,

데이터 수집 기간이 굉장히 오래 걸립니다. 대신 성능은 확실하니 시간 충분히 잡으시고 며칠 걸린다 생각하고 각오하십쇼.
### Set up

    git clone git@github.com:DDalaDDula/NIFoS_Textdata_Analysis.git
    cd NIFoS_Textdata_Analysis

---
### Environment

    conda env create -f NIFOS.yaml   -- 가상환경이 activate 되어있을 때
    conda activate NIFOS

