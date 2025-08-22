 Create a folder add some contents in it, 
 Use ansible playbooks to copy it to remote instance
 Set up git in that instance by either generating the gitkeys or copying it.
 After that go to that folder
 Run git init
 Then git add .
 Then git commit -m “done ansible test”
 Then git remote set origin “repo url”
 Then git push origin main.


Creating Inventory file (inventory.ini):
[remote_host]
54.144.158.82 ansible_user=ubuntu ansible_ssh_private_key_file=/home/ambikac/Downloads/anamika.pem


