# Taxi 133 Project
## _Operator & Admin Dashboard + Driver Application_

### Frameworks used for this project :
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain-wordmark.svg" alt="Laravel" width="32"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React.js" width="32"/>
<img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="Kotlin" width="32"/>

### Description
This project has 2 dashboards for Admin & Operators to handling online cab services.

![alt Operator Dashboard](https://raw.githubusercontent.com/MkBahram/Taxi133-project-about/main/images/operator-dashboard.png)

The routin for take a services and handle it to drivers are described in below :

:one: : Passenger calls to operator

:two: : Operator Takes Passenger Phone And Check it exist in passengers list or not

:three: : If passengers doesnt exist , operator take fullname of passenger and save it as new passenger

:four: : Operator ask about service type (Normal Service,Out of city service,Hourly Service,Package Delivery Service,...)

:five: : Operator take information about origin and destination ( it automatically searches with map api to get cordinates of origin and destination , we used Neshan Maps Api)

:six: : With origin and destination cordinates , system calculates the distance and duration between this 2 points & at last system calculates price of trip with prices what admins set in admin dashboard.

>This service are available in bandarabbas,iran . the employer wants city separates in 6 stations because the services provides in system farely.

>Each driver with drivers application must be entered in queue . when he clicked on Enter To Queue , system takes driver cordinates and calculates driver is in which station , because stations has borders .

:seven: : Service is going to station which is passengers origin cordinates there.

:eight: : Driver can accept service or reject it to next driver.




