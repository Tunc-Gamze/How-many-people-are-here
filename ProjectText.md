# The PoC File Of The Application That Can Measure The Passenger Density On The Bus
## Purpose: 
It is aimed to improve the public transportation services offered by the municipality, to provide communication between the citizen and the municipality and to provide solutions for the needs.
## Requirement:
Data such as line routes, numbers, location information of buses and camera information, and image processing algorithm for image processing function, design of user interfaces, Database needs.
## Application Flow:
Process starts as soon as the driver starts the bus. Along with the operation of the vehicle, the location information of the vehicle, which route it will take, who will do it, what time it is and the vehicle number information are recorded in the database. When passengers start to pick up from the first stop, our camera system starts counting people and saves the data it collects to the database. These data processed in the database meet the users in the user interface.
## Data Sources:
GPS data for bus locations, open data portals / web services for line route and bus numbers. Camera information for image processing.
## Data collection:
Location data from GPS and camera numbers are stored and used in the database.
## Data analysis:
Density is calculated by comparing the person data from the camera with the capacity of the bus. These collected data will be examined in certain periods and will help to find solutions to the needs by providing the interpretation of the habits of the citizens.
## Visualization:
After processing the data we have obtained, it will be presented graphically and this data will be used more effectively.
For example, a heatmap will be used when examining density data. These data will be analyzed retrospectively and the result will be visualized regionally with pie charts and periodically with bar charts.
## Application Interfaces:
#### Note: Images are for illustrative purposes only. It continues to be developed.
Sample Admin Panel
Sample User Panel
Sample User Panel
Sample User Panel
## Database:
We are planning to use MsSql as relational Database and mongoDb as non relational Database
## Future Studies:
Density data obtained will be processed with artificial intelligence and recommendations will be given...








