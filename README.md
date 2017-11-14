# ansible-repo
Repository for ansible playbooks 


## NginX + HLS + ffmpeg Deployment

- Requires Ansible 1.2 or newer
- CentOS hosts

These playbooks deploy a simple configuration of the HLS video streaming platform 
and frontend by the Nginx web server. 

Then run the playbook, like this:

	ansible-playbook -i hosts hls.yml

The playbooks will configure Nginx, ffmpeg, and HLS. When the run
is complete, you can hit access server to begin the video streaming.
