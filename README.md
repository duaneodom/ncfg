# ncfg
Command Line Network Configuration Tool

This is a simple command line network configuration frontend to ifupdown.  It handles network mappings in /etc/network/interfaces and in the drop directory /etc/network/interfaces.d.  Some oddities are that it doesn't support duplicate mapping names even across network devices. It also is only really written with having one interface connected at a time.
