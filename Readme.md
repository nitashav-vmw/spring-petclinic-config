# Spring Petclinic Configuration Repository

ytt -f k8s --ignore-unknown-comments | kapp deploy -n petclinic -a petclinic -y -f -
