# craete-shh-key
1. To generate a new SSH key pair, use the following command: ssh-keygen -t rsa -C "your.email@example.com" -b 4096
2. git config --global user.name "Admin"
3. git config --global user.email "admin@vinasupport.com"


# gitlab to github repo

git clone <old_url>
cd <repo_dir_name>
git remote add new_remote <new_url>
git push --all new_remote
