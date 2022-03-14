  docker run --detach \
  --publish 1443:443 --publish 8080:80 --publish 1001:22 \
  --name gitlab \
  --restart always \
  --volume gitlab_config:/etc/gitlab \
  --volume gitlab_logs:/var/log/gitlab \
  --volume gitlab_data:/var/opt/gitlab \
  --shm-size 2gb \
  gitlab/gitlab-ce:latest
