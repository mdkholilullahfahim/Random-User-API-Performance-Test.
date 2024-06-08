# project Title: Random-User-API-Performance-Test.

## This repository contains a performance test setup for the Random User API using Apache JMeter. The goal is to measure and analyze the performance of the Random User API under various load conditions.

## Prerequisites
- Apache JMeter (version 5.0 or later)
- Java 8 or higher

## Installation
1-Clone the repository

- git clone https://github.com/mdkholilullahfahim/Random-User-API-Performance-Test.git
cd Random-User-API-Performance-Test

2-Download and Install JMeter

- Download JMeter from the official website.
- Extract the downloaded archive to a preferred location on your system.

3-Setup Environment Variables (optional)
- Add JMeter bin directory to your system's PATH variable for easy command-line access.

## Usage
1- Open JMeter
- Navigate to the JMeter bin directory.
- Execute jmeter.bat (Windows) or jmeter (Mac/Linux) to launch the JMeter GUI.

2- Load the Test Plan
- Open the JMeter GUI.
- Click on File -> Open and navigate to the cloned repository.
- Select RandomUserAPI_TestPlan.jmx.

3- Configure Test Parameters (optional)
- Edit the test parameters as needed (e.g., number of threads, ramp-up period, loop count) in the Thread Group section.

4- Run the Test
- Click on the green start button (▶) in the JMeter toolbar.
- Monitor the results in the View Results Tree or Summary Report listeners.

  5- View Results
  - After the test completes, you can analyze the results using various listeners provided in the test plan.
  - Results can be saved and exported for further analysis.
 
## Test Plan

The test plan includes the following components:
- Thread Group: Defines the number of users, ramp-up period, and loop count.
- HTTP Request: Configured to make GET requests to the Random User API.
- Listeners: Includes View Results Tree, Summary Report, and other listeners for monitoring and analyzing the test results.

## Results
Results from the performance tests will be displayed in the configured listeners. Key metrics to analyze include:
- Response Time: Measure the time taken to get a response from the API.
- Throughput: Number of requests processed by the API per minute.
- Error Rate: Percentage of failed requests.

  Results can be exported to CSV or XML format for further analysis and reporting.

## Contributing

Contributions are welcome! Please follow these steps:
- Fork the repository.
- Create a new feature branch (git checkout -b feature/your-feature).
- Commit your changes (git commit -am 'Add new feature').
- Push to the branch (git push origin feature/your-feature).
- Create a new Pull Request.
  
