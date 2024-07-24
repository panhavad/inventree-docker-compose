This is a simplify guide to install Inetree on docker
1. Clone this git to your local machine
2. Modify the `INVENTREE_SITE_URL` to your intented HOST IP
3. Use this command to prepare the environment
   
   `docker compose run --rm inventree-server invoke update`
5. Use this command to bring up the container
   
   `docker compose up`
7. After bring up complete you should be able to access the Inventree via http://your-host-ip
8. This environment by default log in is
   
   Username: `admin`

   Password: `admin123321`

