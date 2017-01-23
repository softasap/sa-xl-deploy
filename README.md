sa-secure-auditd
================
[![Build Status](https://travis-ci.org/softasap/sa-xl-deploy.svg?branch=master)](https://travis-ci.org/softasap/sa-xl-deploy)

XL Deploy is the only application release automation solution that is agentless across all target platforms.
Connect to Windows and Unix target systems using proven, industry-standard remote protocols;
no agent installation and maintenance, no overhead on the target systems, no firewall ports to be opened, and no security reviews.


Example of use: check box-example

Simple:

Installs software, but you need to initialize it manually

```YAML


     - {
         role: "sa-xl-deploy",
         option_init_xl_server: false
       }

```


Advanced:

provides option to perform automatic configuration  

```YAML


     - {
         role: "sa-xl-deploy",
         option_init_xl_server: true,
         xl_admin_password: "admin1234"
       }


```


Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)
