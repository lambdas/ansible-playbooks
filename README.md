# ansible-playbooks
My Ansible playbooks to control Kubernetes clusters.

## setup-node.yml
Sets up a fresh instance of RaspberryPi OS to run a Kubernetes node. After it finishes, you can run `kubeadm` to start a control plane or to join a worker node to an existing cluster. After that install a CNI of your choice.
