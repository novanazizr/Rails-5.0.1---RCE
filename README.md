# Rails-5.0.1---RCE
# Date: 2020-07-19
# Author : Lucas Amorim (lucas@lucasamorim.ca)
# Vendor Homepage: www.rubyonrails.org
# Software Link: www.rubyonrails.org
# Version: Rails < 5.0.1

# CVE-2020-8163 - Remote code execution of user-provided local names in Rails

# Remote code execution of user-provided local names in Rails < 5.0.1

# There was a vulnerability in versions of Rails prior to 5.0.1 that would allow an attacker who controlled the locals argument of a render call.

# This vulnerability has been assigned the CVE identifier CVE-2020-8163.

# Versions Affected: rails < 5.0.1 Not affected: Applications that do not allow users to control the names of locals. Fixed Versions: 4.2.11.2

#How To Install?
1. $apt-get update&&apt-get upgrade
2. $git clone https://github.com/novanazizr/Rails-5.0.1---RCE
3. $cd Rails-5.0.1---RCE
4. $ruby exploit.rb

## Requirement
1. Ruby
