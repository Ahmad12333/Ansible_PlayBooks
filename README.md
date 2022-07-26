# Ansible_PlayBook
# For ansible to work correctly with cisco routers we should configure the hosts file as below
#     [cisco_r:vars]
#	ansible_network_os=ios
#	ansible_password="your router pass"
#	ansible_connection=local
#Because we cant copy the key file into the cisco router we should enable some conf into the ansible.cfg file like below :
#[defaults]
#Host_key_checking = false
#Also we should change the “ansible_network_os”  attribute value in the hosts file into “cisco.ios”

