    1  aws --version
    2  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
    3  ls -ltr
    4  unzip awscliv2.zip
    5  ls -ltr
    6  which aws
    7  sudo ./aws/install --bin-dir /usr/bin --install-dir /usr/local/aws-cli --update
    8  /usr/bin/aws --version
    9  ls -ltr
   10  cd code/
   11  ls -ltr
   12  vi deployment-secret.yaml
   13  ls -ltr
   14  ls -ltra
   15  rm -rf .deployment-secret.yaml.swp
   16  vi deployment-secret.yaml
   17  kubectl apply -f deployment-secret.yaml
   18  kubectl get pods
   19  kubectl exec -it nginx-secret-deployment-86cf6df49b-2tvkk bash
   20  vi pv.yaml
   21  kubectl get deployment
   22  kubectl delete deployemnt/nginx-secret-deployment
   23  kubectl delete deployment/nginx-secret-deployment
   24  ls -ltr
   25  vi deployment-secret.yaml
   26  yum install git -y
   27  sudo yum install git -y
   28  ls -ltr
   29  git init
   30  git add README.md
   31  touch README.md
   32  git add .
   33  git commit -m "updated"
   34  git config --global --edit
   35  git commit --amend --reset-author
   36  git branch -M main
   37  git remote add origin git@github.com:devopsmar2021/k8s-code.git
   38  git push -u origin main
   39  ssh-keygen
   40  cat /home/ec2-user/.ssh/id_rsa.pub
   41  git push
   42  git push --set-upstream origin main
   43  history
