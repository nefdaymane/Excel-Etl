# Excel-Etl
The aim of this project is to facilitate the extraction, transformation, and loading (ETL) process for Excel files. The ETL process is designed to correct errors in Excel files and subsequently store the cleaned data in our database.

# Backend (Node.js, Express.js, Mongoose, MongoDB)
The backend is implemented using **Node.js, Express.js, Mongoose, and MongoDB.** The primary objective of the backend is to dynamically generate services based on a configuration file (config.yaml). By modifying the collection name and columns in the configuration file, a new collection is created with corresponding services. This ensures flexibility and scalability as new collections can be effortlessly added or modified.
## Backend Configuration (config.yaml)
```
**Collection Name:** Specify the name of the collection.
**Columns:** Define the columns for the collection.
```
With this approach, the backend automates the service creation process, allowing for seamless adaptation to changing data structures.

# Frontend (React)

```
**Import Excel File:** Click on the "Import" button to upload an Excel file.
**Column Reorganization:** Utilize the arrow buttons to rearrange columns as needed.
**Order Validation:** Visual indicators will validate whether the current order matches the predefined order.
**Save Data:** Click on the "Save" button to store the data in the database if the order is valid.
```

This project aims to streamline the data processing pipeline, providing a user-friendly interface for ETL operations on Excel files.
