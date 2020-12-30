# Configure Haproxy_loadbalancer and apache_webserver using ansible-roles on AWS
New Task-15...!!

Task Description📄

🔅Create an ansible role myapache to configure Httpd WebServer.
Here, I have created an ansible role as "webserver".

🔅Create another ansible role myloadbalancer to configure HAProxy LB.
Here, I have created an ansible role as "lb".

🔅We need to combine both of these roles controlling webserver versions  and solving challenge for host ip's  addition  dynamically over  each Managed Node  in  HAProxy.cfg file.
For combining both 'lb' and 'webserver' ansible roles playbook , I have created one more ansible role as "project" to combine both playbook in a main_playbook using command :-
# ansible-galaxy init <role_name>

I have done this task on AWS Ec2_instances.

