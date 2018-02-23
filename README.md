## docker-library

kubernetes 相关 images 同步


用下面的命令来生成需要的docker image

docker pull t1zhou/kube-controller-manager-amd64
docker pull t1zhou/kube-scheduler-amd64
docker pull t1zhou/kubedns-amd64
docker pull t1zhou/kube-proxy-amd64
docker pull t1zhou/pause-amd64
docker pull t1zhou/kube-dnsmasq-amd64
docker pull t1zhou/exechealthz-amd64
docker pull t1zhou/etcd-amd64
docker pull t1zhou/kube-apiserver-amd64
docker pull t1zhou/kube-discovery-amd64
docker pull t1zhou/k8s-dns-sidecar-amd64
docker pull t1zhou/k8s-dns-dnsmasq-nanny-amd64
docker pull t1zhou/k8s-dns-kube-dns-amd64

docker tag t1zhou/etcd-amd64:latest gcr.io/google_containers/etcd-amd64:v3.1.10
docker tag t1zhou/kube-controller-manager-amd64 gcr.io/google_containers/kube-controller-manager-amd64:v1.9.3
docker tag t1zhou/kube-scheduler-amd64 gcr.io/google_containers/kube-scheduler-amd64:v1.9.3
docker tag t1zhou/kubedns-amd64 gcr.io/google_containers/kubedns-amd64:v1.9
docker tag t1zhou/kube-proxy-amd64 gcr.io/google_containers/kube-proxy-amd64:v1.9.3
docker tag t1zhou/pause-amd64 gcr.io/google_containers/pause-amd64:v3.0
docker tag t1zhou/kube-dnsmasq-amd64 gcr.io/google_containers/kube-dnsmasq-amd64:v1.4.1
docker tag t1zhou/exechealthz-amd64 gcr.io/google_containers/exechealthz-amd64:v1.2
docker tag t1zhou/kube-apiserver-amd64 gcr.io/google_containers/kube-apiserver-amd64:v1.9.3
docker tag t1zhou/kube-discovery-amd64 gcr.io/google_containers/kube-discovery-amd64:v1.0
docker tag t1zhou/k8s-dns-sidecar-amd64 gcr.io/google_containers/k8s-dns-sidecar-amd64:v1.14.7
docker tag t1zhou/k8s-dns-dnsmasq-nanny-amd64 gcr.io/google_containers/k8s-dns-dnsmasq-nanny-amd64:v1.14.7
docker tag t1zhou/k8s-dns-kube-dns-amd64 gcr.io/google_containers/k8s-dns-kube-dns-amd64:v1.14.7

docker rmi t1zhou/kube-controller-manager-amd64
docker rmi t1zhou/kube-scheduler-amd64
docker rmi t1zhou/kubedns-amd64
docker rmi t1zhou/kube-proxy-amd64
docker rmi t1zhou/pause-amd64
docker rmi t1zhou/kube-dnsmasq-amd64
docker rmi t1zhou/exechealthz-amd64
docker rmi t1zhou/etcd-amd64
docker rmi t1zhou/kube-apiserver-amd64
docker rmi t1zhou/kube-discovery-amd64
docker rmi t1zhou/k8s-dns-sidecar-amd64
docker rmi t1zhou/k8s-dns-dnsmasq-nanny-amd64
docker rmi t1zhou/k8s-dns-kube-dns-amd64



