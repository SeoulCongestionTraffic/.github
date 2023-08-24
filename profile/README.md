# 서울시 도시 혼잡도  (공사 중)
<div class="center">
  <img width="800" alt="image" src="https://github.com/SeoulCongestionTraffic/.github/assets/52487610/18292116-f70e-4760-ac6e-4721a9c0b3ac">
</div>

## 3개의 repository
1. KafkaCongestionStreaming [API 호출 -> pydantic -> kafka] 
2. SparkCOngestionStreaming [spark streaming -> [kafka, mysql]]
3. TrafficBackend [backend]


### 실행 방법 
1. KafkaCongestionStreaming (python async_congestion.py)
```python async_congestion.py```

2. SparkCOngestionStreaming
```python spark_connection/rate_congestion.py```
