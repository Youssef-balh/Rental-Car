This is a C# .NET Framework application with a MySQL database to manage car rental operations. It provides features for storing information about cars, clients, rentals, charges, and statistics.

## Features

- **Dashboard**: Overview statistics including the number of cars rented, charges, revenues, and charts displaying net profit, return time, insurance time, and technical issues time.
  
- **Car Management**: Allows adding, modifying, deleting cars, and searching for cars.

- **Rental Management**: Displays a list of rented cars with information such as the rented car's matricule, client name, rental dates, paid amount, and remaining amount. The status of a rental switches to "returned" automatically after the current date exceeds the arrival date.

- **Client Management**: Lists clients with a feature to mark them as blacklisted.

- **Charges Management**: Lists charges with corresponding dates.

- **Credit Management**: Tracks the monthly credit of cars, including the amount left and the remaining months to pay.

- **Statistics Overview**: Provides a statistics overview where users can choose a specific period and view revenues and expenses.

- **Backup and Restore**: Option to backup the MySQL database and restore from a backup.

- **Login**: Includes a login feature for user authentication.

## Backup and Restore

This application includes a feature to backup and restore the MySQL database. You can create a backup of the database using the provided functionality. Similarly, you can restore the database from a previously created backup file.

To perform a backup, navigate to the backup section in the application and follow the on-screen instructions. To restore a database from a backup, select the option to restore and provide the path to the backup file.

## Technologies Used

- C# .NET Framework for the application development.
- MySQL database for storing information.


| ![Capture d'écran 2024-03-23 175519](https://github.com/Youssef-balh/Rental-Car/assets/113738047/143b4d57-5b0c-4811-863e-d22d27b6f95b) | ![Capture d'écran 2024-03-23 175505](https://github.com/Youssef-balh/Rental-Car/assets/113738047/baf0677d-3002-4a97-8ab7-f2d9335f4a41)|
| --- | --- |
| ![Capture d'écran 2024-03-23 175658](https://github.com/Youssef-balh/Rental-Car/assets/113738047/b549e85a-0872-4f5f-958e-b670d3d3a0b4) | ![Capture d'écran 2024-03-23 175532](https://github.com/Youssef-balh/Rental-Car/assets/113738047/74dbedda-76a6-42d9-98af-bf634f59df1d) |

