## ShellScript-OpenStack-Xena

This script can be used to deploy OpenStack-Xena on CentOS 8-stream. Use this script to complete the entire deployment process, except that the deployment process does not include the deployment of Storage nodes.

![](https://github.com/bcYwpK3/ShellScript-OpenStack-xena/blob/main/Screenshots.jpg)

## Requirements

You need to prepare a clean and minimally installed CentOS 8-stream server.  You need to manually specify hostname and fixed IP address to make sure they are connected to each other.

## Document overview
~~~
├── 1-Controller-base.sh      # This is the basic configuration for the control node on which it should run.
├── 2-Other-base.sh           # This is the base configuration for other nodes, which should run on other nodes besides the control node.
├── 3-Controller-keystone.sh
├── 4-Controller-glance.sh
├── keyston-script            # This is a folder where keyston variables are stored.
│   └── admin-openrc          # This is the variable file used for authentication on the client side.
├── LICENSE                   # This is an open source license file.
├── .openstack_password
├── README.md                 # This is a must-read file.
└── Screenshots.jpg           # This is an architectural picture.
~~~
to be added.............

**！！！After the minimum installation, do not perform any operations. Modify and run the project script based on the system environment  ！！！**

## Dependencies

- Operating system version: CentOS 8/8-STREAM or RHEL 8
- You need at least one Controller node, one Compute node, and one Neutron node.
- The Controller node requires at least 2 cpus and 4GB memory.
- The Compute node requires at least 2 cpus, 4GB memory, and 80 GB disks.
- The Neutron node requires at least 1 cpus and 2GB memory.

## License

BSD 3-Clause

## Author Information

E-Mail: hacker.xiaoyin@gmail.com

QQ: 914258259

