# pfSense-speedup
A collection of pfSense System patches to speed up the dashboard

 - **find_rule_by_number_alt.patch**: alternative to find_rule_by_number() on log.widget.php
 - **find_rule_by_number.patch**: speed up of find_rule_by_number() on syslog.inc
 - **get_interface_info.patch**: little patch to get_interface_info() on pfsense-utils.inc
 - **mbuf_load.patch**: speedup of get_mbuf() and get_load_average() on functions.inc.php
 - **get_sysctl.patch**: speedup of get_sysctl() on util.inc

**WARNING: this patches are tested with CE 2.7.2 only**
