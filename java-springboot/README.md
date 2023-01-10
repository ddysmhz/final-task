# Prequisition
 * Follow the use case from Curriculum Probation App Team

## How To Deployment ?
 * Include the script wait-for-it.sh to waiting database running and connect the service.
 * Create CI until build and scan images.
 * Don't push a credentials to your repository.

## This command to hit endpoint and makesure your application is running
 * curl --header "Content-Type: application/json" --request POST --data '{"empId":"13","empName":"pablo"}' https://final-task.obrol.id/insertemployee 

## This is expected result after you deploy and hit the endpoint.
 * open https://final-task.obrol.id/employees

![Result](img/result.jpg)