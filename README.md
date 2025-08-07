# Relational-music-Database
Music Store Database
This project contains the SQL schema for a Music Store database created using pgAdmin 4's ERD tool.

📁 Tables Included
artist

album

track

genre

media_type

playlist

playlist_track

customer

employee

invoice

invoice_line

🔗 Relationships
Albums link to artists

Tracks link to albums, genres, and media types

Playlists contain tracks

Invoices belong to customers and contain invoice lines

Employees can report to other employees

Customers are assigned to support reps (employees)

<img width="710" height="574" alt="MusicDatabaseSchema" src="https://github.com/user-attachments/assets/72939d47-4f95-4383-b71a-c525f0f3e6b7" />
