# A dockerized app that computes the hourly amount of fees spent by transactions between EOA on Ethereum Blockchain

Function **calculateHourlyEthFeeBetweenEOA** makes the required query and calculate the hourly ethereum fees between externally owned accounts.

# EndPoint

You can get the JSON response from  ```/getfee```

# Run the project
- Go the project folder
- Run docker
- Build the project: ```docker-compose build```
- Run the project: ```docker-compose up``` (Some multiple runs may be necessary.)
- Go to end point : [externaly owned accounts]: http://localhost:8080/getfee