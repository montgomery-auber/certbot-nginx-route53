This repo will create your certs in docker-volumes/etc/letsencrypt/

the files there in the live dir are just symbolic links, the originals are in the archive dir

put your email address after --email 
put your domain name that needs the create after the -d 
REMEMBER for  a real cert to remove --staging (for testing) 

to run it do docker compose -f docker-files/docker-compose.yaml up