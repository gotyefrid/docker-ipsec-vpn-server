# Installation

1. **Install Docker**  
   On the VPS server, you need to install Docker first.

2. **Prepare Configuration Files**  
   Place the files `docker-compose.yml` and `vpn.env` in the desired directory (e.g., `~/vpn`).

3. **Edit Configuration**  
   Edit the `vpn.env` file as you wish, or leave it as it is (unsafe).

4. **Run the Docker Compose Command**  
   Execute the following command:
   ```bash
   docker compose up -d
   ```
   
5. In the directory where docker-compose.yml is located, a folder ikev2-vpn-data will be created in which files for clients (vpnclient.mobileconfig vpnclient.p12 vpnclient.sswan) will be created.  
Read more at https://github.com/hwdsl2/docker-ipsec-vpn-server/tree/master
