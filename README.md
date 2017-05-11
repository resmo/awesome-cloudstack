[![Build Status](https://travis-ci.org/resmo/awesome-cloudstack.svg?branch=master)](https://travis-ci.org/resmo/awesome-cloudstack)
# Awesome Apache CloudStack

> A curated list of bookmarks, projects, tutorials, videos and other cool resources from the CloudStack ecosystem.

## Table of Contents

- [Essentials](#essentials)
- [Packages and Images](#packages-and-images)
- [Command Line Interface Clients](#command-line-interface-clients)
- [Configuration Management Integrations](#configuration-management-integrations)
- [Libraries](#libraries)
- [Operational Extensions](#operational-extensions)
- [Videos](#videos)
- [Articles, Tutorials, Blogs, etc.](#articles-tutorials-blogs-etc)
- [Development](#development)
- [Community](#community)


## Essentials

* [Apache CloudStack](http://cloudstack.apache.org/)
* [CloudStack Installation Guide](http://docs.cloudstack.apache.org/projects/cloudstack-installation/)
* [CloudStack API Reference](http://cloudstack.apache.org/api.html)


## Packages and Templates

### Installation Packages

* [Install Packages from ShapeBlue](http://www.shapeblue.com/packages/)
* [Install Packages from PCextreme](http://cloudstack.apt-get.eu/)

### Templates

* [Pre-Build Instance Templates](http://dl.openvm.eu/cloudstack/)
* [SystemVM Packer](https://github.com/MissionCriticalCloud/systemvm-packer)
* [Instance Templates Packer](https://github.com/MissionCriticalCloud/bubble-templates-packer)


## Command Line Interface Clients

* [Apache Cloudmonkey (Python)](https://github.com/apache/cloudstack-cloudmonkey)
* [cloudstack-cli (Ruby)](https://github.com/niwo/cloudstack-cli)
* [cs (Python)](https://github.com/exoscale/cs)
* [go-cloudstack](https://github.com/xanzy/go-cloudstack)


## Configuration Management Integrations

### Ansible
* [Ansible CloudStack Modules (built-in)](http://docs.ansible.com/ansible/list_of_cloud_modules.html#cloudstack)
* [Ansible CloudStack Guide](http://docs.ansible.com/ansible/guide_cloudstack.html)
* [Ansible Cloud Infra Role (Advanced Networking)](https://github.com/swisstxt/ansible-role-cloud-infra)

### Terraform
* [CloudStack Provider](https://www.terraform.io/docs/providers/cloudstack/)

### Vagrant
* [Vagrant Cloudstack Provider ](https://github.com/MissionCriticalCloud/vagrant-cloudstack)

## Libraries

* [cs (Python)](https://github.com/exoscale/cs)
* [go-cloudtack (Go)](https://github.com/xanzy/go-cloudstack)
* [golang-cloudstack-library (Go)](https://github.com/atsaki/golang-cloudstack-library)
* [cloudstack-php (PHP)](https://github.com/PCextreme/cloudstack-php)
* [cloudstack_client (Ruby)](https://github.com/niwo/cloudstack_client)
* [Apache libcloud (Python)](https://libcloud.apache.org/)
* [Apache jclouds (Java)](https://jclouds.apache.org/)
* [apache-cloudstack-java-client (Java)](https://github.com/Autonomiccs/apache-cloudstack-java-client)
* [apache-cloudstack-javascript-client
(JavaScript)](https://github.com/Autonomiccs/apache-cloudstack-javascript-client)


## Operational Extensions

### Montitoring and Graphs

* [CloudStack Nagios Montitoring by SWISS TXT](https://github.com/swisstxt/cloudstack-nagios)
* [collectd-cloudstack plugin](https://github.com/exoscale/collectd-cloudstack)
* [CloudstackStats into InfluxDB](https://github.com/niwo/cloudstack_stats)

### RealHostIP replacement

* [nip.io fork for realhostip service](https://github.com/resmo/nip.io)
* [powerdns-cloudstack-proxy-dns](https://github.com/terbolous/powerdns-cloudstack-proxy-dns)

### Billing Solutions

* [HostBill (commercial)](http://hostbillapp.com/feature/cloudstack-overview/)
* [Amysta (commercial)](http://www.amysta.com/)
* [StratoSTACK](http://stratostack.org/)
* [Cyclops](icclab.github.io/cyclops/)


### Misc

* [CloudStack Chaos Monkey](https://github.com/resmo/cloudstack-chaosmonkey)
* [Alternative CloudStack-UI by Bitworks Software, Ltd.](https://bwsw.github.io/cloudstack-ui/)

## Videos

* [Introduction to Apache CloudStack by David Nalley](https://www.youtube.com/watch?v=1MDLg-wxB6g)
* [CloudOps Channel](https://www.youtube.com/channel/UC0FMV0TSW6jvSRGC26r4-Gw)


## Articles, Tutorials, Blogs, etc

* [ShapeBlue Blog](http://www.shapeblue.com/blog/)
* [Remi Bergsma's blog](https://blog.remibergsma.com/tag/cloudstack-2/)
* [shankerbalan.net](https://shankerbalan.net/)


## Development

### Main

* [GitHub](https://github.com/apache/cloudstack)
* [Apache CloudStack Issue Tracker](https://issues.apache.org/jira/browse/CLOUDSTACK)

### Continuous Integrations

* [Trillian](https://github.com/shapeblue/Trillian)
* [bubble-blueprint](https://github.com/MissionCriticalCloud/bubble-blueprint)

## Community

* [Mailing Lists](http://cloudstack.apache.org/mailing-lists.html)
* IRC: `irc://irc.freenode.net/cloudstack`
* [Slack](https://apachecloudstack.slack.com)

## Contributing

Found an awesome project, blog, video etc.? Send me a pull request!

### Guidelines

* Please make an individual pull request for each suggestion
* Make sure the TravisCI tests pass on your pull request
* Use the following format for links: \[Resource\]\(URL\)
* Want to suggest a package? Read the [Contribution Guide](https://github.com/chiraggude/awesome-laravel/blob/master/CONTRIBUTING.md)
* New categories or improvements to the existing categorization are welcome

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Awesome CloudStack is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
