CMS (Complaint Management System)
===

> This is the repository for reporting bugs and for development of the CMS Framework. 


### Installing at a local server:


> 1. Copy all the files to the root directory of your local server.

> 2. Upload the `cms.sql` to MySQL using `phpmyadmin`, default configuration is:
>          
>         Host: localhost
>         User: root
>         Pass: 
>         Db: cms
> If these differ in your machine, then you will have to update the new details at:
>          
>         admin/core/control/all_connect.php
>         admin/core/control/conn.php
>         admin/core/welcome.php
>         user/core/control/all_connect.php
>         user/core/control/conn.php
>         user/welcome.php
>
> 3. Log in at the `Admin Control Panel` using `http://127.0.0.1/admin/` with the following credentials:
>
>         Email: neeraj@gmail.com
>         Pass:  neeraj
>
> 4. New users can be created from the registration form at the home page. Existing user:
>
>         Email: tanay@gmail.com
>         Pass : tanay
>
> 5. Happy Hacking!


### Contributing to the Repository:

> `This project is now deprecated! PRs won't be accepted.`
