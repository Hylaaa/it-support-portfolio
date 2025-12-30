# Linux Users & Permissions Lab

This lab covers basic user management and file permissions in Linux.

## Commands Practiced

### whoami
Check current logged-in user.
```bash
whoami
```

### id
View user ID and group information
```bash
id
```

### ls -l
Check file permissions
```bash
ls -l
```

### chmod
Change file permissions
```bash
chmod 755 script.sh
chmod u+x file.sh
```

### chown
Change file owner
```bash
sudo chown user:user file.txt
```

### useradd
Create a new user
```bash
sudo useradd testuser
```

### passwd
Set password for a user
```bash
sudo passwd testuser
```

### su
Switch user
```bash
su testuser
```

## What I Learned
How Linux permissions work (read, write, execute)
Difference between owner, group, and others
Basic user account management
Importance of permissions for system security

