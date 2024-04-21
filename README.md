# Generatecode
I show how create a database with randoms values from Python to Postgres from this problem: 

Write a Python script that generates random data for a logistics application in Spain. The script should create CSV files for companies, drivers, vehicles, clients, and parcels. Each file should contain a specified number of entries with randomly generated data.

The generated data should follow these guidelines:

Companies: Each company entry should include a unique CIF (tax identification code), name, address, province, email, and phone number. The email addresses and phone numbers should be unique across all companies.
Drivers: Each driver entry should include a unique DNI (personal identification number), name, contract date, phone number, salary, and the CIF of the company they work for. DNI and phone numbers should be unique across all drivers.
Vehicles: Each vehicle entry should include a unique license plate, brand, model, kilometers, registration date, and the DNI of the driver assigned to the vehicle. The license plates should be unique across all vehicles.
Clients: Each client entry should include a unique client ID, name, address, province, email, and phone number. The client IDs, emails, and phone numbers should be unique across all clients.
Parcels: Each parcel entry should include a unique parcel ID, origin and destination addresses, origin and destination provinces, weight, departure date, arrival date, license plate of the vehicle used, and the client ID associated with the parcel.
The script should generate the specified number of entries for each file and save them as CSV files in the current directory. Make sure to include headers for each CSV file.



