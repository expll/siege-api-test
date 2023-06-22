# vegeta 做API压力测试

```
brew install vegeta
vegeta attack -duration=60s -rate=1 -targets=requests.txt | vegeta report

requests.txt
GET http://47.104.103.63/1.json

```
