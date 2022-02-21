# TestCase
	TestCase for Genesis DevOps school
<ol>	
<li>Real OS Windows 10</li>
<li>Virtualbox 6.1.32 </li>
<li>Virtual OS Ubuntu 20.04.3 LTS</li>
<li>ansible [core 2.12.2]</li>
<li>python version = 3.8.10 (default, Nov 26 2021, 20:14:08) [GCC 9.3.0]</li>
<li>jinja version = 2.10.1</li>
<li>pip 22.0.3</li>


	
</ol>
Tested between Ubuntu 20.04.3 LTS and 20.04.3 LTS running on VirtualBox 6.1.32

Before run please change files:
<ul>
<li> <b>inventory</b>  - set correct <b>IP-address</b> instead of <i>'10.0.2.7'</i></li>
<li> <b>inventory</b>  - set correct <b>ansible_ssh_user</b> instead of <i>'serveruser'</i></li>
<li> <b>ansible.cfg</b>  - set correct <b>remote_user</b> instead of <i>'serveruser'</i></li>
</ul>

Run command
<code>
$ cd ansible_docker_wordpress; ansible-playbook install_docker.yaml
</code>
