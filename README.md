# centos7

docker build -t danielucb/centos7:7.9.2009 .

docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  danielucb/centos7:7.9.2009