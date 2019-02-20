# Part 1: Kubernetes YAML
k8s_yaml(listdir("kubernetes-manifests"))

# Part 2: Docker Images
docker_build("adservice", 'src/adservice')
docker_build("emailservice", 'src/emailservice')
docker_build("productcatalogservice", 'src/productcatalogservice')
docker_build("recommendationservice", 'src/recommendationservice')
docker_build("shippingservice", 'src/shippingservice')
docker_build("checkoutservice", 'src/checkoutservice')
docker_build("paymentservice", 'src/paymentservice')
docker_build("currencyservice", 'src/currencyservice')
docker_build("cartservice", 'src/cartservice')
docker_build("frontend", 'src/frontend')
docker_build("loadgenerator", 'src/loadgenerator')

# Part 3: Resources
k8s_resource("frontend", port_forwards="8080")
