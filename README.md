# Ansible Playbook for DHCP & OSPF Automation on Cisco
Configure IP Address, DHCP Server and OSPF automatically using Ansible

This repository contain Ansible Playbook to Configure IP Address, DHCP Server and OSPF automatically. You can automate OSPF & DHCP Configuration with differents topology using this script. You just need to edit the vars file to meet the topology that you have. The vars file is located in https://github.com/arrosid/ansible_ospf_dhcp/blob/master/roles/generate_config/vars/main.yml

<h3>Requires</h3>
<ul>
  <li>ansible 2.6.4</li>
</ul>
<h3>Supports</h3>
<ul>
  <li>This script support for Cisco IOS</li>
</ul>

<h3>How to use</h3>
<ul>
  <li>Ensure you setup the topology</li>
  <li>Configure Management IP Address and enable SSH in the router</li>
  <li>Ensure you have ansible installed on your computer</li>
  <li>Edit the vars file to meet your topology</li>
  <li>Run the script <i>ansible-playbook site.yml</i></li>
</ul>
