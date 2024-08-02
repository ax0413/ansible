ansible.cfg 파일에서 user가 다른 경우 수정하세요

inventory 파일에서 control-plane, worker-node의 ip에 맞게 수정하세요

pwd가 ~/ansible이 맞는지 확인하세요

ansible-playbook [FILE.yaml]

docker: docker.yaml
kubernetes: k8s.yaml
control-plane(kubeadm init): master.yaml
worker-node(kubeadm join): worker.yaml
rook: ceph.yaml
machbase: machbase.yaml
