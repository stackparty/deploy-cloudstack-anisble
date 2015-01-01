deploy-cloudstack-anisble
=========================
rpm -ivh http://www.mirrorservice.org/sites/dl.fedoraproject.org/pub/epel/6/i386/epel-release-6-8.noarch.rpm
yum install -y ansible
ansible-playbook deploy-cloudstack.yml -k
