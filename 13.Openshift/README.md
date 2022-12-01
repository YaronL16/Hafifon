# Openshift

### Intro
- What is the difference between OpenShift and Kubernetes

### Openshift Resources
- Route
    - Why are Routes useful?
    - How does a Route work?
    - What are the different types of TLS Terminations that can be used by Routes?
    - How does a request to a route's URL reaches the Service?
    - How do Routes work in our tactic environment (Helper)?
- CSR
    - What are CSR's used for?
    - How are CSR's renewed?
    - What can cause an expiriration of cluster certificates? (Often happens in our cloudlets)

### Cluster Operators
What is the responsiblity of the following Cluster Operators?

- authentication
- console
- etcd
- ingress
- openshift-apiserver
- machine-config
- network
- dns
- image registry

### Openshift Installation
- Read about ignition files for OpenShift and the Bootstrap process of a cluster
- What is the different between UPI and IPI installations (User/Installer provisioned installation)?
- What is a Kubernets CSI? Why is it important to setup right after the installation of a cluster?


### Custom Operators
- What is the difference between an operator and a controller?
- Read about the [creation of ansible operators](https://docs.openshift.com/container-platform/4.6/operators/operator_sdk/osdk-ansible.html)

### Tactic environment
- Read and understand the Ansible Tower workflow for installing a Cloudlet
    - Login to Ansible Tower in our environment (Ask a team member to help)
    - Go to Templates
    - Search for "Deploy Full Cloudlet" Workflow Template
    - Click on Workflow Visualizer, and for each playbook:
        - Go to Projects
        - Search for the playbook's project
        - Go to the git URL specified in the project, and read the playbook referenced in the Job Template for that project
    - Note: Check out the roles and `requirements.yml`, many roles are used in the workflow playbooks
    - Note: If you want to dive deeper and understand every role, 
            you can read the Hafifon in Confluence to get a better understanding of our environment
