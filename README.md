# pfSense-speedup
A collection of pfSense System patches to speed up the dashboard. This is a WIP code review based on design patterns, avoid reiteration of exec(), shell_exec() and avoiding the execution of piped commands.

 - **util.inc.patch**: speedup of isvalidpid(), is_process_running(), get_sysctl(), route_table() on util.inc
 - **functions.inc.php.patch**: speedup of get_mbuf(), get_load_average() on functions.inc.php
 - **pfsense-utils.inc.patch**: speedup of get_interface_info() on pfsense-utils.inc
 - **syslog.inc.patch**: speedup of find_rule_by_number(), get_port_with_service(), dump_log(), conv_log_filter() on syslog.inc

**WARNING: this patches are tested with CE 2.7.2 only**
