# graylog-siem-ansible-ubuntu

## An ansible playbook for setting up [graylog based siem](http://#)

    ansible-playbook -i hosts playbook.yml

Set the variables in playbook.yml according to your environment.
    
    interface_name: "ens3"
    
    graylog_ip: "1.1.1.1"
    
    ossec_port: "5141"
    
    snort_port: "5142"
    
    snoopy_port: "5143"

###  Note 1: Comment out the roles that you don't need.
###  Note 2: Change the host file according to your environment
 
