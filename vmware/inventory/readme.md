#### Configuration:
AAP -> Inventories -> Add -> Add Inventory -> Name:vmware-inventory -> Save -> Sources -> Add -> Name:vmware-inventory-source -> Source:vmware vcenter -> Credential:Select vcenter credential
 -> Source Variables:Paste the variables from file vmware-invetory-source.yml -> Save -> Sync

#### Verification:
AAP -> Inventories -> Check Groups and Hosts

#### Scheduling:
AAP -> Inventories -> Sources -> vmware-inventory-source -> Schedules -> Add
