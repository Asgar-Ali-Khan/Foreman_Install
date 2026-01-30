Notes / operational guidance (important for Katello)
Fresh system requirement
Foreman docs recommend a freshly provisioned system because the installer alters several components. [docs.theforeman.org]
Ports
For Katello external connections, the Katello docs call out these required ports:

80/tcp (HTTP)
443/tcp (HTTPS)
5647/tcp (qdrouterd)
9090/tcp (Smart Proxy communication) [downloads....oreman.org]

If you plan to manage Puppet agents, the Katello scenario includes Puppet server capability, so 8140/tcp may be needed for agent traffic.