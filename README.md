To Check Centos Version
# yum install redhat-lsb-core
#lsb_release -d

Docker Container for Kafka Instance

docker network create --driver bridge spark-net 

docker run --name kafka0 --hostname kafka0 -p 9092:9092 -p 8081:8081 -p 2181:2181 –p 9999:9999 -i -t --privileged --network spark-net -v /tmp:/Software centos /usr/sbin/init

Kafka SOftware

https://drive.google.com/drive/folders/1Ch4c5PezfHhUAlMiuu6TMA6Tl4xDei8j?usp=share_link
