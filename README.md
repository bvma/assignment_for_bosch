# bosch_app
 
#For performance we should use the syncronize module that is based on rsync.
#The syncronize module is not working with variable
#If you need to use variable for path use the copy module
# COPY MODULE WAS ENABLED BY DEFAULT

In the host file please update/modify the used variables
Default variables in inventory file:
- ansible_ssh_user=root
- ansible_ssh_pass=1234
- app_port=3000
- app_name=bosch_app
