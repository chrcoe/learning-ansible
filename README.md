# Learning Ansible

this repo is helping me document/track my changes while following along with the [ansible introduction](http://docs.ansible.com/intro.html)

to use a playbook-:
	
	ansible-playbook <playbook.yml> -i <inventory file> -f 10

So for this ansible setup:

	ansible-playbook site-dir.com/site.yml -i site-dir.com/dev-hosts -f 10

the "-f 10" argument runs 10 parallel operations ... this is not required
