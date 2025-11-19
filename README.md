# remt_serv
setting up ssh server with keys and connect on other pc
https://roadmap.sh/projects/ssh-remote-server-setup

Install and enable SSH server on the Ubuntu VM.

Generate two SSH key pairs inside the VM (id_rsa_vm1 and id_rsa_vm2).

Add both public keys to the VM’s ~/.ssh/authorized_keys.

Copy the private keys into a shared folder (<shared_folder>) for transfer to the host.

Move the private keys into the host’s ~/.ssh/ directory.

Configure networking (Host-Only or Bridged) and confirm the VM IP address.

Test SSH connections from the host using both keys.

(Optional) Create an SSH config file on the host with aliases for easier connections.

(Optional) Install and configure Fail2Ban with a custom jail to protect SSH from brute-force attempts.
