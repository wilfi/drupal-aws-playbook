# drupal-aws-playbook

This repository contains a starter Ansible playbook to host a Drupal on Amazon Linux. 

The playbook can be used to perform the task on a `cloud-init` 

Refer https://github.com/wilfi/terraform-get-started.git

The playbook will install and enable

1. PHP and required extensions
2. NGINX
3. Composer
4. Drush
5. Drupal latest stable version and install with Standard profile
6. Cloudwatch agent (For logging)
