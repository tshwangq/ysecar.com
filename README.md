# ysecar.com
广州永松电动车有限公司


# 搭建方案
- 采用wordpress 搭建
- 采用docker 部署

# 步骤
- copy docker file 
   
  scp -r . root@ysecar.com:~/

- run docker 

  docker-compose up
  
- copy theme

  scp -r autocar root@ysecar.com:/var/www/html/wp-content/themes/
