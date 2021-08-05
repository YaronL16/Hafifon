Recommended to do after you learned at least loops.

Run on 2 nodes:
1. deploy nginx
2. pass a jinga template of nginx configuration file:
    1. FQDN and port as group parameters
    2. root as host parameters
3. pass a different html file to each node/server
4. check outside HTTP access to the servers using the parameters you configured with - must be a part of the playbook!

Be creative! Add error handling, roles and etc. enjoy!
