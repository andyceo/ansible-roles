ansible-roles
=============

# About project #

This project store common reusable Ansible roles. All documentation and examples are provided by [ansible-example](https://github.com/andyceo/ansible-example) github project.

# System requirements #

This version of roles was tested only on:

  - Ubuntu 13.10
  - Ansible 1.4.4+dfsg-1~ubuntu13.10.1 (installed from backports: `sudo aptitude install ansible/saucy-backports`)

Previous versions of Ansible and Ubuntu are not supported. If you interested in its support, please, provide patches. We plan to support further versions if Ubuntu LTS releases and Ansible stable releases.

Previous versions of Ansible and Ubuntu are not supported. If you interested in its support, please, provide patches.

You need first install required roles from Ansible Galaxy:

    cd ansible
    ansible-galaxy install andyceo.preconf andyceo.mailutils andyceo.mc andyceo.git andyceo.php andyceo.apache andyceo.composer andyceo.drush
