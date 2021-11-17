# 工程简介
admin client test

as nacos client; 
integrate actuator; 
config 
```
management:
  endpoints:
    web:
      exposure:
        include: '*'
#  endpoint:
#    health:
#      show-details: always
```
unnecessary dependent on admin client
it can be monitored with admin server via nacos