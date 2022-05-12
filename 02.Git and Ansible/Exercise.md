Recommended to do after you've learned at least loops.

Run on 2 nodes:
1. deploy nginx
2. pass a Jinja template of nginx configuration file:
    1. FQDN and port as group parameters
    2. root as host parameters
3. pass a different html file to each node/server
4. check outside HTTP access to the servers using the parameters you configured with - must be a part of the playbook!

* Notice - you may encounter a problem accessing your site due to firewall rules. Run the following command on the two nodes:
systemctl stop firewalld 
This will turn off the firewall service. It is a not recommended temporary solution, but you will learn about it later on in Networking.

Be creative! Add error handling, roles and etc. enjoy!
