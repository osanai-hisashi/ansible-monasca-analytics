# MoNanas Ansible

## Installation

### Get the Code
```
git clone https://github.com/openstack/monasca-vagrant
```

### Edit requirements.yml
Add the following lines in requirements.yml.
```
- src: https://github.com/osanai-hisashi/ansible-monasca-analytics
  name: monasca-analytics
```

### Install VirtualBox and Vagrant
Note: Vagrant version 1.5.0 or higher is required.

#### Linux (Ubuntu)
```
sudo apt-get install virtualbox
#Download and install latest vagrant from http://www.vagrantup.com/downloads.html
sudo pip install ansible  # Version 1.8+ is required
ansible-galaxy install -r requirements.yml -p ./roles
```


## License
Copyright (c) 2016 Fujitsu Limited
Licensed under the Apache License, Version 2.0 (the "License"); you may not
used this file except in compliance with the License. You may obtain a copy of
the License at:
```
http://www.apache.org/licenses/LICENSE-2.0
```
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations under
the License.
