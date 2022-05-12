# Openshift

### Intro
- What is the difference between OpenShift and Kubernetes

### Openshift Resources
- Route
    - How does a Route work?
    - How does Route differ from Ingress?
    - How do Routes work in our tactic environment?
- CSR
    - What are CSR's used for?
    - How are CSR's renewed?
    - What can cause an expiriration of cluster certificates? (Hint: Often happens in cloudlets)
- DeploymentConfig
    - How does DeploymentConfig differs from Deployment?
- Project
    - How does Project differ from Namespaces?

### Cluster Operators

1. authentication
2. console
3. etcd
4. ingress
5. openshift-apiserver
6. machine-config
7. network
8. dns
9. image registry

### Network flow

Understand the network flow of a packet into the pod of an openshift cluster.


### Openshift Installation
- How to install openshift on bare metal and vsphere
    - Igition files
    - bootstrap
- What is the different between UPI and IPI installations (User/Installer provisioned installation)?
- Read about Kubernetes CSI
    - How do CSI's work in OpenShift? 

### Custom Operators
- What is the difference between operator and a controller?
- Read about the [creation of ansible operators](https://learn.openshift.com/ansibleop/ansible-operator-overview/?extIdCarryOver=true&sc_cid=701f2000001OH7YAAW)

### Tactic environment
- Read and understand the Ansible Tower workflow for creating a Cloudlet
    - Login to Ansible Tower in our environment (Ask a team member to help)
    - Go to Templates
    - Search for "Deploy Full Cloudlet" Workflow Template
    - Click on Workflow Visualizer, and for each playbook:
        - Go to Projects
        - Search for the playbook's project
        - Go to the git URL specified in the project, and read the playbook referenced in the Job Template for that project
    - Note: Check out the roles and `requirements.yml`, many roles are used in the workflow playbooks
- Read the Troubleshooting OCP doc in the tactic environment

