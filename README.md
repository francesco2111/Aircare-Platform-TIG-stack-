# Aircare-Platform-TIG-stack-
This repository contains the instructions and configuration files needed to set up a TIG (Telegraf, InfluxDB, and Grafana) infrastructure for collecting, storing, and visualizing data from an air quality monitoring sensor, specifically the Aircare device, as part of environmental measurement campaigns.

To recreate the TIG infrastructure, follow these steps:

	1.	Clone the repository to your local machine using the command:
		git clone https://github.com/francesco2111/Aircare-Platform-TIG-stack-.git

	2.	Open a terminal and navigate to the newly cloned folder:
		cd Aircare-Platform-TIG-stack-

	3.	Edit the .env file to update the environment variables used for configuring and deploying the stack.

	4.	Customize the telegraf.conf file, which will be mounted into the container as a persistent volume, to tailor the configuration to your data source.

	5.	Launch the infrastructure by running the command:
		docker-compose up -d --build
  
This will build the Docker containers and start the Telegraf, InfluxDB, and Grafana services.
