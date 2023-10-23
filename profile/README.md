# 서울시 도시 혼잡도 
<div class="center">
  <img width="800" alt="image" src="https://github.com/SeoulCongestionTraffic/.github/assets/52487610/189b0ed6-6641-47e1-b702-0bb3929a7608">
</div>


## 3개의 repository
1. KafkaCongestionStreaming</br>
   1.1. [API 호출 -> pydantic -> kafka] 
2. SparkCOngestionStreaming </br>
   2.1. [Kafka -> [sink-connection -> s3 -> athena], [backend(fastapi)]]   
4. TrafficBackend [backend]


### 실행 방법 
1. KafkaCongestionStreaming 
```python async_congestion.py```

2. SparkCOngestionStreaming
```python spark_connection/rate_congestion.py```

3. TrafficBackend
```sudo docker compose up --build```
