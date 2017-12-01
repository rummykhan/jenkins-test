Jenkins Testing
--

### Flow
1. Install Jenkins [https://jenkins.io/download/](https://jenkins.io/download/).
2. Add a virtual host in nginx/apache configuration.
3. Restart Nginx
4. Login as jenkins `sudo su jenkins`
5. Create ssh key for jenkins to add to VCS(Version Control System). `ssh-keygen`
6. Add `.id_rsa.pub` to VCS SSh Keys.
7. Exit from `jenkins` user.
8. Add `jenkins` to `www-data` group `sudo adduser jenkins www-data`
9. Open jenkins in web
10. Start writing jenkins job.


### Contact
[rehan_manzoor@outlook.com](mailto://rehan_manzoor@outlook.com)
