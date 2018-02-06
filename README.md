# Blinux
A secure Linux Distro based on Bodhi
The goal here is security for the masses by acting as a admin while preserving the OS as a whole and not being too in your face.
The goal here is to lose some privacy (but we should have a strong privacy policy) to have a secure computer. Starting with 
a iptable script broken up to 7 users with SELinux labeling. Filters (level 3) based on bad words (porn keywords). 
Blacklists from peergardian runing psad fwsnort and fwknop (for admin access) has blacklists for bad websites (porn)
using open family DNS. Ipset rules for whitelists and built in network controls (local) based on user (guid) it also has
a secure list which when activated (with the -I command) allows only the website (banks). Logs diffrent state (nlgroup)
in ulogd based on issue. It is a all inclusive script so triwire can be run on it and loaded with iprestore ipset is made to
be updated when going online.
Tripwire runs only PAM login, blowfish keys iptable script, SElinux policy and rsynce to my server.
Iptables is loged to server and optionally someone else.
Logs all access from users.
PAM ACL.
When avalible TPM.
And some command lines blocked such as su dpending on the user.
