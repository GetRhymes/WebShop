curl -X POST -H 'Content-Type: application/json' -d '{"id":6,"name":"prod1","count":12}' 'http://localhost:8080/goods/admin/addGoods' -u admin:admin
curl http://localhost:8080/goods/ -u user:user | json_pp  
curl -X POST http://localhost:8080/goods/buyGoods -u user:user -d 'id=6'