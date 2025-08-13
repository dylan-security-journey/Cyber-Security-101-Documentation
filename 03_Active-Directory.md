## Windows Domain

A single repository is created known as active directory which helps control everything under a domain to make sure all systems are configured properly under windows (centralized control)


<img width="480" height="380" alt="image" src="https://github.com/user-attachments/assets/0ee68bcc-2392-4807-aee7-6f82dec1611e" />

The server in charge of the active directory is known as domain controller

<img width="1115" height="559" alt="image" src="https://github.com/user-attachments/assets/4dbf133f-939f-4fc0-90da-1ab8114061b1" />

<img width="1002" height="416" alt="image" src="https://github.com/user-attachments/assets/6f8c8478-b258-4362-80f9-abde13b25a8c" />

In the image above, example of OUs and how they are broken uo by departments with users in each OU

Users can be members of a single OU at a time dependent on applying policies rather security groups users can be grouped in many because of accessing different resources

domain admins are responsible for administiring all computers and resources in that particular domain

$ is used to associate machines with accounts 

Sometimes in order to delete an OU, you must change view to advanced features and apply changes of protect obhect from accidental deletion

<img width="585" height="570" alt="image" src="https://github.com/user-attachments/assets/95feddfe-9a76-4398-bd83-c71026bc2677" />

Delegate control to philip over an OU

<img width="1060" height="256" alt="image" src="https://github.com/user-attachments/assets/85114afb-c5a9-4887-a87b-1a8b9d7e670a" />

logged in as a user that we delegated changing the password of another user account in a different OU

<img width="658" height="403" alt="image" src="https://github.com/user-attachments/assets/96f8977c-4263-4f3f-945c-5c053762bdfd" />

It's important to tidy up workstations, domain controllers, and servers to segregate policies based on usage instead of having it all in the computers section

<img width="1216" height="860" alt="image" src="https://github.com/user-attachments/assets/3999f6d6-2a23-4181-9093-84a741ca36ce" />

Group Policy Objects are assigned to OUs to set rules and GPM can help change the password for computers and etc 

<img width="274" height="43" alt="image" src="https://github.com/user-attachments/assets/13741d59-850c-40a5-9be8-6dc4ca2dde4b" />

this can be applied to desired computer for automatic updates from the GPO

<img width="781" height="556" alt="image" src="https://github.com/user-attachments/assets/6efcb295-4c16-40a3-b222-1625ae1858e6" />

creating a policy for device inactivity leads to lock screen after 300 seconds

<img width="603" height="178" alt="image" src="https://github.com/user-attachments/assets/304f3148-7e85-44c7-a67f-056b03b38e5a" />

Example of effect of applying GPO to prohibit access of control panel 

SYSVOL is the network that distributes GPOs across computers

<img width="1042" height="361" alt="image" src="https://github.com/user-attachments/assets/2378e624-d386-41d4-9477-8ee73237a604" />

<img width="1042" height="409" alt="image" src="https://github.com/user-attachments/assets/779896ed-3218-4282-9d4d-44f2f9fce84d" />

<img width="1027" height="311" alt="image" src="https://github.com/user-attachments/assets/8f8028d5-b5fc-4ced-a012-050e3fdd983c" />

Kerberos Authentication above

<img width="1034" height="517" alt="image" src="https://github.com/user-attachments/assets/a5a350b1-fda6-4cff-8f9e-eb903f5ae640" />

NetNTLM Authentication above

<img width="937" height="599" alt="image" src="https://github.com/user-attachments/assets/a4d8d11e-48c8-428a-b6fd-c2ab313cdfff" />

Each country has their own domain controller when it comes to scalability

<img width="993" height="405" alt="image" src="https://github.com/user-attachments/assets/82df4fbf-a158-481a-b957-31ad86ee74b3" />

Forest occurs when domains join 

<img width="616" height="265" alt="image" src="https://github.com/user-attachments/assets/4b70ce27-e289-44b2-8912-3bb7f4e1b2c4" />

one-way trust relationship






























