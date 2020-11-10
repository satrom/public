# Docker管理面板Portainer中文汉化项目

第一步：docker pull portainer/portainer
第二步：git clone https://github.com/satrom/public.git
第三步：docker run -d -p 9000:9000 --restart=always  -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data -v /public:/public --name prtainer portainer/portainer
