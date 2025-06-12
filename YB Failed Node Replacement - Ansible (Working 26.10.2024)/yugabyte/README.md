Role Name
=========

Playbook.yml

This Playbook Add the New Node and Remove the Failed Node from the YB-Cluster and Restart YB-services in all nodes except Failed one.

Prequesties:

SSH Connectivity: Ensure SSH access is set up among the nodes with the necessary private keys. Confirm that passwordless SSH is configured between Node1, Node2, the Failed Node, and the New Node.

Requirements
------------
What We need?

Provide these variables in the script before running it:

Private IPs:

Yb1 - Private IP for Node1
Yb2 - Private IP for Node2
failed - Private IP for the Failed Node
new - Private IP for the New Node
yugabyte_base_path - Path where YugabyteDB is installed on each node (e.g., /home/ubuntu/yugabyte-{{ yugabyte_version }})


Author Information
------------------

Managed IT - @Justo_Global