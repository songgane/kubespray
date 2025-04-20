- user
```
1  pyenv activate kubespray
   23  cd /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray/
   55  cd /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray
   57  pyenv activqt kubespray
   58  pyenv activate kubespray
   59  pyenv activate kubespray
   66  pyenv activate kubespray
   67  cd /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray
   86  pyenv activate kubespray
   88  pyenv activate kubespray
  103  history | grep kubespray
sh: git_prompt_info: command not found
ai-frontier(base) %(?:%{%}%1{➜%} :%{%}%1{➜%} ) %{%}%c%{%} history
    1  pyenv activate kubespray
    2  ls -al
    3  pwd
    4  ssh testw04
    5  whoami
    6  vi /etc/profile 
    7  pip list
    8  ssh testm01
    9  ssh-copy-id testm01
   10  vi ~/.ssh/known_hosts
   11  ssh-keygen -t rsa
   12  sed -i 's/.$//' ~/.oh-my-zsh/lib/git.zsh
   13  ssh-keygen -t rsa
   14  ssh testm01
   15  ssh-copy-id testm01
   16  ssh-copy-id testm01
   17  ssh testm01
   18  ssh testm02
   19  ssh testw04
   20  ssh testw05
   21  ssh testw06
   22  pwd
   23  cd /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray/
   24  ls
   25  ansible -i tlake-inventory.ini all -m shell -a "whoami" --become --become-user=root
   26  ansible -i /Users/songgane/Dev/conf/tlake-inventory.ini all -m shell -a "whoami" --become --become-user=root
   27  ansible -i /Users/songgane/Dev/conf/tlake-inventory.ini all -m shell -a "whoami" --become --become-user=root
   28  ansible -i /Users/songgane/Dev/conf/tlake-inventory.ini all -m shell -a "whoami" 
   29  ssh testm02
   30  ssh-copy-id testm02
   31  ansible -i /Users/songgane/Dev/conf/tlake-inventory.ini all -m shell -a "whoami" 
   32  ssh-copy-id testw03
   33  ssh-copy-id testw04
   34  ssh-copy-id testw05
   35  ssh-copy-id testw06
   36  ansible -i /Users/songgane/Dev/conf/tlake-inventory.ini all -m shell -a "whoami" 
   37  vi /Users/songgane/Dev/conf/tlake-inventory.ini
   38  ansible -i /Users/songgane/Dev/conf/tlake-inventory.ini all -m shell -a "whoami" 
   39  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml
   40  pwd
   41  ssh testw04
   42  cd ~
   43  ls
   44  cd ~/.ansible/
   45  ls
   46  cd cp/
   47  ls
   48  rm -rf *
   49  cd ~
   50  ls
   51  ls -rlt
   52  rm ctxusbd_*
   53  ls
   54  ls -rlt
   55  cd /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray
   56  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml
   57  pyenv activqt kubespray
   58  pyenv activate kubespray
   59  pyenv activate kubespray
   60  cd ~
   61  ls
   62  vi /etc/profile
   63  sudo vi /etc/profile
   64  vi ~/.bash_profile
   65  source ~/.bash_profile 
   66  pyenv activate kubespray
   67  cd /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray
   68  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml
   69  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml
   70  ls  -al ~/.ansible/
   71  ls  -al ~/.ansible/tmp/
   72  ls  -al ~/.ansible/cp/
   73  rm -rf ~/.ansible/cp/*
   74  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml
   75  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml -vvv
   76  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml
   77  pwd
   78  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags cilium
   79  ping testcw01.thadoop.skt
   80  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags cilium
   81  ls
   82  pwd
   83  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags apps,ingress-nginx,ingress-controller
   84  history
   85  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml
   86  pyenv activate kubespray
   87  source ~/.bash_profile
   88  pyenv activate kubespray
   89  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml
   90  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags kube-master
   91  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags kube-apiserver
   92  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags kube-apiserver -e upgrade_cluster_setup=true
   93  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags kube-apiserver
   94  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags kube-apiserver -e upgrade_cluster_setup=true
   95  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root upgrade-cluster.yml --tags cilium
   96  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root upgrade-cluster.yml 
   97  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --limit=kube_control_plane
   98  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags cilium
   99  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root upgrade-cluster.yml --tags cilium
  100  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags cilium
  101  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml --tags cilium,krew
  102  ansible-playbook -i inventory/tlake_ns2/inventory.ini  --become --become-user=root cluster.yml
```


- root
```
37  conda env remove kubespray
   39  conda-env remove kubespray
   40  conda-env remove -n kubespray
   45  mv kubespray k8s
  311  source activate kubespray
  312  conda activate kubespray
  352  conda create -n kubespray python=3.9.15
  353  cd ~/Dev/src/github/k8s/kubespray
 1040  docker run -ti -v /Users/songgane/Dev/src/github/k8s/kubespray:/root/kubespray centos:7
 1050  docker run -d -ti -v /Users/songgane/Dev/src/github/k8s/kubespray:/root/kubespray centos:7
 1052  docker cp 3680e72f155b:/root/k8s/kubespray.tar .
 1056  docker run --previliged=true -d -ti -v /Users/songgane/Dev/src/github/k8s/kubespray:/root/kubespray centos:7
 1057  docker run --previliged -d -ti -v /Users/songgane/Dev/src/github/k8s/kubespray:/root/kubespray centos:7
 1058  docker run --previliged -d -ti -v /Users/songgane/Dev/src/github/k8s/kubespray:/root/kubespray centos:7 /sbin/init
 1059  docker run --priviliged -d -ti -v /Users/songgane/Dev/src/github/k8s/kubespray:/root/kubespray centos:7 /sbin/init
 1060  docker run --privileged -d -ti -v /Users/songgane/Dev/src/github/k8s/kubespray:/root/kubespray centos:7 /sbin/init
 1067  docker run --privileged --cgroupns=host -v /sys/fs/cgroup:/sys/fs/cgroup:rw -d -ti -v /Users/songgane/Dev/src/github/k8s/kubespray:/root/kubespray centos:7 /sbin/init
 1070  docker cp kubespray.tar 4e71f22241d4:/root
 1083  scp root@192.168.1.20:/root/kubespray/kubespray-offline.tar .
 2064  cd /Users/songgane/Downloads/kubespray/무제\ 폴더/kubespray-offline 
 2076  scp root@192.168.1.20:/root/kubespray/kubespray-offline-2.19.1.tar .
 6282  git clone https://github.com/kubernetes-sigs/kubespray.git
 6283  rm kubespray
 6306  pyenv virtualenv 3.11.6 kubespray
 6447  k apply -f /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray/extra_playbooks/inventory/tlake_ns2/hubble-ui-ingress.yml -n kube-system
 6669  cd /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray/roles/kubernetes-apps
 6670  pyenv activate kubespray
 6938  du -h -d 1 /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray
 6939  rm -rf kubespray
 7036  cp roles/kubernetes-apps/ingress_controller/ingress_nginx/defaults ../k8s-ops/kubespray/roles/kubernetes-apps/ingress_controller/ingress_nginx/defaults
 7037  cp roles/kubernetes-apps/ingress_controller/ingress_nginx/defaults/main.yml ../k8s-ops/kubespray/roles/kubernetes-apps/ingress_controller/ingress_nginx/defaults
 7038  cp roles/container-engine/validate-container-engine/tasks/main.yml ../k8s-ops/kubespray/roles/container-engine/validate-container-engine/tasks/main.yml
 7039  cp MINE.md ../k8s-ops/kubespray
 7040  cp -r inventory/tlake_ns2 ../k8s-ops/kubespray/inventory/
 7046  git commit -m 'add custom kubespray'
 7497  cd ../kubespray
 7524  ls -al kubespray
 7526  git commit -m 'add new components: kubespray'
 7712  cd /Users/songgane/Dev/src/gitlab/k8s/ops/kubespray
 7713  git remote add origin https://github.com/songgane/kubespray.git
 7715  git clone https://github.com/songgane/kubespray.git 
 7716  cd kubespray
10524  cd ../../kubespray
10528  git remote add upstream https://github.com/kubernetes-sigs/kubespray
```