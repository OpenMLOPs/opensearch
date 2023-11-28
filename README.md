# OPENSEARCH STACK
## Steps
1. Step 1: Run the following docker command
   ```
    docker compose -p "opensearch" up
   ```
2. Step 2: Stop and Run fluent-bit service
3. Step 3: Login to Opensearch dashboard on browser
   ```
    http://localhost:5601/app/home#/
   ```
4. Step 4: Click on Manage link on home page
   
   ![image](https://github.com/OpenMLOPs/opensearch/assets/32771325/83c892de-eb72-48ae-945d-3e30bcbeed60)
  
5. Step 5: Click on Index patterns link under Manage

   ![image](https://github.com/OpenMLOPs/opensearch/assets/32771325/c546f5ac-9d03-419e-b105-ae0abd826de9)

6. Step 6: Click on create index pattern

   ![image](https://github.com/OpenMLOPs/opensearch/assets/32771325/a473cd58-dc28-48bc-8575-ac2cecb31dca)

7. Step 7: Type Name of Index and Click on Next

   ![image](https://github.com/OpenMLOPs/opensearch/assets/32771325/b73189ea-a2bd-4a7f-833e-e765a05fbd1c)

8. Step 8: On left side Menu Click on discover, you should be able to see your logs

   ![image](https://github.com/OpenMLOPs/opensearch/assets/32771325/ff848249-4892-4589-8d3c-5f3d16288738)

   ![image](https://github.com/OpenMLOPs/opensearch/assets/32771325/2b68a2c6-5cb7-408a-bf01-a0b9dfbe2d0b)

## Use Cases
1. Centralized Logging Tool
## References:
1. https://github.com/opensearch-project/data-prepper/tree/main/examples/log-ingestion
2. https://opensearch.org/docs/latest/install-and-configure/install-opensearch/index/

## RoadMap
1. Creation of different container based application with opensearch able to accept logs from different services
2. Addition of Application Metric Logs
3. Addition of security layer to restrict accesss to opensearch container

## Issues:
1. Search for solution to avoid stop and start fluent-bit service due to connection error
