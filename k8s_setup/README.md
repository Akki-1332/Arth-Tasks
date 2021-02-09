# What to Do ==>>
## Must Read It First...

1. Change you AWS Credentials in the file **aws**.
2. Make Sure your AWS Instances have tag names : `master` for Master Node and `worker` for Worker Node. (**Case-Sensitive**)
3. You can Run **master.yml** file to Configure **kubernetes Master Node** using `ansible-playbook master.yml` command.
4. You can Run **worker.yml** file to Configure **kubernetes Worker Node** using `ansible-playbook worker.yml` command.
5. You have to change some more things to make it work properly. (**Read Instructions**)
   - Go Inside **aws_host** folder.
   - Go inside **files** folder of Both **master** and **worker** folder.
6. Don't Change Any other File.

## Where to store.. =>>
- Download complete folder **k8s_setup**.
- 
