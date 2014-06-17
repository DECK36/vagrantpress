# VagrantPress

*VagrantPress* is a packaged development environment for developing WordPress themes and modules.  
I initially created this project to aid in developing child modules for a WordPress blog.

see https://github.com/chad-thompson/vagrantpress for more info

# CI-Box

Inside this branch I test some setup options for better testing inside the VM.

So far I changed the HTTP port to 8080 to have the same URL inside and outside
the VM in order to run Behat tests.

Further plans include a puppet refactoring and using Composer instead of PEAR
for global pkg installs.
