docker_build(
    'ghcr.io/tinkerbell/cluster-api-provider-tinkerbell',
    '.',
    dockerfile='Dockerfile',
)
k8s_yaml(kustomize('./config/default'))
default_registry('ttl.sh/meohmy-dghentld')