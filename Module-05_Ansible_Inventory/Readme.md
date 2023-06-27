# [Ansible Inventory](https://docs.ansible.com/ansible/latest/inventory_guide/intro_inventory.html)

## What is an Ansible Hosts file?
  - Ansible Host file (also known as inventory) defines the managed nodes configurations that you automate, with groups so you can run automation tasks on multiple hosts at the same time.
  - Once your inventory is defined, you use patterns to select the hosts or groups you want Ansible to run actions on it.
  - The simplest inventory is a single file with a list of hosts and groups.
  - The default location for this file is <b>*/etc/ansible/hosts*</b>.
  - You can specify a different inventory file at the command line using the -i <path> option or in configuration using inventory.
  - The most common inventory file formats are:
    - <b>*INI*</b>
    - <b>*YAML*</b>
  - Sample inventory file
    ```
      appserver.novatec.com
      
      [webservers]
      webserver1.novatec.com
      webserver2.novatec.com
      webserver3.novatec.com
      
      [dbservers]
      dbserver1.novatec.com
      dbserver2.novatec.com
    ```
## Passing multiple inventory sources

## Organizing inventory in a custom directory

## Adding Variables to the inventory file

## Ansible Inventory: INI Format | Groups | Groups within Groups

## Ansible Inventory: YAML Format | Groups | Groups withing Groups

## [Examples]()

## Working with Dynamic Inventory
