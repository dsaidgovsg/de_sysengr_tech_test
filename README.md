# Technical Assessment for DE Sys Engr

### Base OS

1. Update and upgrade the OS packages

2. Add admin group - ag_adm, gid=1001; ad_usr, gid=1002

3. Create new users - john (group `ad_usr`) and adm-john (group `ag_adm`)

4. Allow `ag_adm` sudo users to run administrative commands.

### Docker
5. Install `docker` and `docker-compose`. 

6. Ensure docker is started up at boot-up.

7. Pull the postgres docker image.

8. Start up the Postgres Server using either docker run or docker-compose.

### IPv6
9. Disable IPv6

10. Verify that IPv6 is disabled.

### JDK
11. Install OpenJDK with JRE.

### Access.conf
12. Configure /etc/security/access.conf to only allow hdadmin, adm-john and john to login via the network (not LOCAL), and deny everyone else from everywhere.
