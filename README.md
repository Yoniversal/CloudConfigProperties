# Doc: https://www.cnblogs.com/fengzheng/p/11242128.html
# Webhooks
## For automatically triggering http://localhost:clientPort/actuator/refresh, in order to get updated value from cloud
## Step: Setting -> Webhooks -> Add webhook
## If we have multi clients, better option is 'Spring Cloud Bus', which requires message queue(RabbitMQ or kafka)
### After setting the cloud bus which trigger multi-client, need to add webhook in Setting for /actuator/bus-refresh