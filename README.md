# docker-registry
setup private docker registry for kubernetes with persistent volume

helm install -f values.yml docker-registry  twuni/docker-registry

helm get manifest  docker-registry  > registry-manifest.yml

helm uninstall docker-registry



