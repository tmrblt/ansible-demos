## Prerequisites:

Guest customization requires installing Perl and applying the following settings to the templates.

**RHEL/CentOS:**
```bash
yum install perl -y
vmware-toolbox-cmd config set deployPkg enable-custom-scripts true
```

**Ubuntu:**
```bash
apt-get install perl -y
vmware-toolbox-cmd config set deployPkg enable-custom-scripts true
```

**Verify Settings:**
```bash
[root@localhost ~]# cat /etc/vmware-tools/tools.conf
[deployPkg]
enable-custom-scripts = true
```
#### References:
- [1] https://docs.vmware.com/en/VMware-vSphere/8.0/vsphere-vm-administration/GUID-EB5F090E-723C-4470-B640-50B35D1EC016.html
- [2] https://docs.vmware.com/en/VMware-vSphere/7.0/com.vmware.vsphere.vm_admin.doc/GUID-9A5093A5-C54F-4502-941B-3F9C0F573A39.html
