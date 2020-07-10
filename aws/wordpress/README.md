```bash
> apt-add-repository ppa:ansible/ansible
> apt-get update
> apt-get install -y ansible
> ansible --version
> ssh-keygen #/home/user/.ssh/omermuhtar
> ssh-add ~/.ssh/omermuhtar
> ssh-add -l
> aws configure --profile omermuhtar
> aws ec2 describe-instances --profile omermuhtar # test profile
> aws route53 create-reusable-delegation-set --caller-reference 1224 --profile omermuhtar
```