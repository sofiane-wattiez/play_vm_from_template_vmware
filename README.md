# Created and play vm from template vmware vsphere

- [x] [Play vm from template vmware](#Play-vm-from-template-vmware)

## play_vm_from_template_vmware:vars

| variable            | mandatory | description                               | exemple                                               |
| ------------------- | :-------: | ----------------------------------------- | ----------------------------------------------------- |
| vmw_hostname        |  **yes**  | Vcenter hostname                          | **hostname**                                          |
| vmw_username        |  **yes**  | Vcenter user                              | **datacenter\jdoe**                                   |
| vmw_password        |  **yes**  | Vcenter password user                     | **password**                                          |
| vmw_instance_name   |  **yes**  | Instance name                             | **test_vm-ansible**                                   |
| vmw_template_name   |  **yes**  | Template name ISO in VCENTER              | **CentOS7-Template**                                  |
| vmw_datacenter_name |  **yes**  | Datacenter Name                           | **Datacenter_Name**                                   |
| vmw_folder_path     |  **yes**  | folder path                               | **/datacenter/vm/Environnement/jdoe**                 |
| vmw_cluster_name    |  **yes**  | Cluster Name                              | **Cluster_name**                                      |
| vmw_wait_tools      |    no     | yes or no                                 | **yes**                                               |
| vmw_wait_custo      |    no     | yes or no                                 | **yes**                                               |
| vmw_dns_servers     |    no     | DNS Server Adress                         | **DNS.ADRESS**                                        |
| vmw_dns_suffixes    |    no     | Suffixe dns                               | **suffixe.dns**                                       |
| vmw_sys_hostname    |    no     | VM sytem hostname                         | **test2-ansible**                                     |
| vmw_datastore       |  **yes**  | Name of datastore                         | **silver**                                            |
| vmw_memory_mb       |    no     | VM Memory value in Megabytes (1000 = 1gb) | **8000**                                              |
| vmw_vcpu            |    no     | Number of vcpu                            | **1**                                                 |
| vmw_vcpu_socket     |    no     | Number of vcpu by socket                  | **1**                                                 |
| vmw_network_name    |  **yes**  | Network Name                              | **jdoe**                                              |
| vmw_connect_network |    no     | Connect network when started : yes or no  | **yes**                                               |
| vmw_ip              |    no     | VM ip adress                              | **100.100.100.100**                                   |
| vmw_netmask         |    no     | VM netmask adress                         | **255.255.255.0**                                     |
| vmw_gateway         |    no     | VM gateway adress                         | **100.100.100.100**                                   |
| vmw_disk_size       |  **yes**  | disk size (GB value)                      | **50**                                                |
| vmw_disk_type       |  **yes**  | VM Disk type                              | **"thin" or "thick" or "None" or "eagerzeroedthick"** |
| vmw_disk_datastore  |  **yes**  | VM Disk Datastore                         | **disk_datastore**                                    |
