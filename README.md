## 🚀 How to Recreate the TIG Infrastructure

Follow these steps:

1. **Clone the repository to your local machine**
   ```bash
   git clone https://github.com/francesco2111/Aircare-Platform-TIG-stack-.git

2.	**Navigate to the project directory**
    ```bash
    cd Aircare-Platform-TIG-stack-
    
3.	**Edit the .env file**
    Update the environment variables to configure and deploy the stack according to your requirements.

4.	**Customize the telegraf.conf file**

    This file will be mounted into the Telegraf container as a persistent volume.

    Adapt it to fit your specific data source (e.g., the Aircare sensor).

5.	**Build and run the infrastructure**
    ```bash
    docker-compose up -d --build
This command will build the Docker containers and start the Telegraf, InfluxDB, and Grafana services.
