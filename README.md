Ansible Cert Processing

Here are two sample playbooks that demonstrate how to use Ansible to manage certs on Brocade switches.

The first playbook generates a keypair and a csr on the switches and then exports the csr to a server for signing.  The second playbook takes signed certs in a directory and pushes them along with the CA cert back out to the switches.  The signing of the csrs is left as an exercise for the reader.
