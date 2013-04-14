fail2ban-0.8.4-OpenSolaris
======================
fail2ban from original 0.8.4 tarball at http://sourceforge.net/projects/fail2ban/files/

Changes to get it to run on OpenSolaris 5.11 snv_134 with /usr/local/bin/python2.7

Follow main [README](README) to install but use python2.7:

	cd fail2ban-0.8.4
	/usr/local/bin/python2.7 setup.py install

Then follow the instructions in [README.Solaris](README.Solaris). 

<del>Just note that you may need to:

	sudo mkdir /var/run/fail2ban 
</del>
