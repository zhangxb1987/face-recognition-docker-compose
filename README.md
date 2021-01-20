docker-compose up


-- 对比
curl -v localhost:8080/api/face/match -X POST -d @test-data.json --header "Content-Type: application/json" --header "X-Auth-Token: access-token-of-admin"

--查询
curl -v localhost:8080/api/face/query/1 -X GET --header "X-Auth-Token: access-token-of-admin"
