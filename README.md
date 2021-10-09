# Taxi 133 Project
## _Operator & Admin Dashboard + Driver Application_


This project has 2 dashboards for Admin & Operators to handling online cab services.

![alt Operator Dashboard](https://raw.githubusercontent.com/MkBahram/Taxi133-project-about/main/images/operator-dashboard.png)

The routin for take a services and handle it to drivers are described in below :

1: Passenger calls to operator

2: Operator Takes Passenger Phone And Check it exist in passengers list or not

3: If passengers doesnt exist , operator take fullname of passenger and save it as new passenger

4: Operator ask about service type (Normal Service,Out of city service,Hourly Service,Package Delivery Service,...)

5: Operator take information about origin and destination ( it automatically searches with map api to get cordinates of origin and destination , we used Neshan Maps Api)

6: With origin and destination cordinates , system calculates the distance and duration between this 2 points & at last system calculates price of trip with prices what admins set in admin dashboard.

>This service are available in bandarabbas,iran . the employer wants city separates in 6 stations because the services provides in system farely.

>Each driver with drivers application must be entered in queue . when he clicked on Enter To Queue , system takes driver cordinates and calculates driver is in which station , because stations has borders .

7: Service is going to station which is passengers origin cordinates there.

8: Driver can accept service or reject it to next driver.
