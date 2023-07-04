# Odoo Old Dependencies

This repo consist of command that can be used to help install older version of Odoo, regardless community or enterprise.
Running `dpkg -i odoo.deb` somehow comes to dependency issue. What you can do is : 

1. Make sure to install pip3
`apt-get install python3-pip`

2. Look into folders in this repo based on your version you want to install, copy-paste what's inside apt-get file to your terminal/console/ssh

3. If you found .dpkg file inside these folder, that means it's Odoo dependency which is obsolete from pypi (mostly no one maintain it anymore). Just clone this repo and install it manually using `dpkg -i *.deb`
