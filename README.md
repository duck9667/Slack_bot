# Slack을 활용한 뉴스봇 제작하기
- 슬랙은 글로벌 협업툴로 다양한 기능을 API, Webhook등으로 제공한다. 
- `BeautifulSoup`을 활용하여 크롤링한 내용을 Webhook을 통해 슬랙의 특정 채널로 전달한다.
- bot생성 및 token발행은 구글링을 통해 쉽게 따라할 수 있다. 

![그림5](https://user-images.githubusercontent.com/33515088/107921848-799b1300-6fb2-11eb-8fc8-3f666a98094b.png)

# 개선점
- 해당 뉴스봇을 주기적으로 자동으로 실행시키기 위해 GCP를 활용했다.
- GCP를 통해 클라우드 상에서 cronjob을 실행했다.
