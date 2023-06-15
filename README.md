# rtCamp-Assignment
Hello...here i mention Procedure for deploy a WordPress Image and Mysql image with the help of docker-compose.yaml

First i take a Ec2 Instance T2micro launch .

create a bash file for install a Docker And Docker Compose.

create a docker-compose.yaml for create a container. Using WordPress and Mysql Image.

"docker-compose up -d" - to run docker-compose.yaml file.

Mention Port 80 is open for WordPress container in YAML file

To create the /etc/hosts entry for example.com pointing to localhost, you can use the following command:

echo "127.0.0.1 example.com" | sudo tee -a /etc/hosts

To prompt the user to open example.com in a browser, you can use the following message:

echo "Open http://example.com in your browser to access the site."

To enable/disable the site by starting/stopping the containers, you can use the following commands as subcommands:

Start the containers

docker-compose up -d

Stop the containers

docker-compose down

To delete the site by deleting the containers and local files, you can use the following command as a subcommand:

Delete the containers and volumes

docker-compose down -v

Delete local files

rm -rf ./wordpress ./db

Thank you..


