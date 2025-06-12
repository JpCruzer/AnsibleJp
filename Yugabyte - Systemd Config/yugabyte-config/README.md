Role Name
=========

Yb_Config

Requirements
------------

If you are going to run this in Visual Studio Code,

Perquisites: Extensions: Ansible,Yaml

Role Variables
--------------
vars/main.yml :

Make sure to add your YB_instances Private IPs in "yugabyte_masters" Variable.

**Important:** Carefully review all relevant files, such as `tasks/main.yml` and `vars/main.yml`, for any location or IP address changes. It's crucial to update these variables correctly - missing even one can lead to the failure of the entire cluster.


Author Information
------------------

Team: Managed IT
Company: Justo_Global
