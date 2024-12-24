# Locust_Performance_testing
This project is designed for performance testing using Locust, an open-source load testing tool. The tests simulate user traffic to evaluate the performance and scalability of the API.

Locust docs - https://docs.locust.io/en/stable/

1. Create a virtual environment (optional):
   ```bash
   python -m venv venv
   ```
   a. Activate the virtual environment:
      - For Linux/macOS:
         ```bash
         source venv/bin/activate
      - For Windows:
         ```bash
         venv\Scripts\activate
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the performance tests with Locust:
    ```bash
    locust --host https://restful-api.dev/
   
4. Once the command is executed, open a browser and go to:
    ```text
    http://localhost:8089
    ```
   a. Set the number of users and spawn rate to start the load test.