Ansible Role: Google Chrome
=========

[![Build Status](https://travis-ci.org/webarchitect609/ansible-role-google-chrome.svg?branch=master)](https://travis-ci.org/webarchitect609/ansible-role-google-chrome)

Installs Google Chrome from the official deb repository.

Requirements
------------

None.

Role Variables
--------------

None of the variables need to be altered for installing the latest stable version of the application. 
However, all available variables are listed below, along with default values (see `defaults/main.yml`):

    chrome_package: google-chrome-stable
    
Package name to install
    
    chrome_deb_source: "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main"
    
Repository url.
    
    chrome_gpg_key_url: "https://dl-ssl.google.com/linux/linux_signing_key.pub"

GPG key url.


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: webarchitect609.google_chrome }

License
-------

MIT

Author Information
------------------

This role was created in 2019 by Gripinskiy Sergey.
