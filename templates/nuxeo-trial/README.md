# Nuxeo

This templates deploys a Trial Nuxeo server. This means it uses an embedded
database, embedded elasticsearch and can't scale.

# How to use it ?

Just create and launch the stack. After that, you have to point a load balancer of you infrasctructure to the internal stack load balancer. 

We made this choice, since it allows to start several Nuxeo server instance on the same infrastructure.

After that you can login with the regular user/password combination Administrator/Administrator.