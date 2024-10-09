Overview
This is an Android application developed using Android Studio and Java. The app is designed to manage a library system with both user and admin interfaces, allowing users to search for books and admins to manage library resources. The application stores its data using Firebase.

Key Features
User and Admin Interfaces:

Admin Interface: Admins can manage library resources by adding floors, racks, and books.
User Interface: Users can search for books and view their location in a grid format.
Three-Level Book Visualization:

Floors: Library floors are managed by the admin.
Racks: Each floor contains several racks.
Books: Books are stored in the racks.
Search and Grid Display:

Users can search for books. The location is visualized in a grid format.
Red-colored buttons on the grid indicate where the searched book is located.
Firebase Integration:

All book, floor, and rack data is stored and retrieved from Firebase Realtime Database.
Features Breakdown
Admin Capabilities:
Add Floors: Admins can create and organize multiple library floors.
Add Racks: Racks can be added to each floor by the admin.
Insert Books: Books are assigned to specific racks.
User Capabilities:
Search Books: Users can search for their desired books.
Visualize Book Location: The searched book's location is shown on a rack grid. Red-colored buttons highlight racks that contain the searched book.
Tech Stack
Language: Java
IDE: Android Studio
Database: Firebase Realtime Database
UI Components: XML layouts and Buttons for rack visualization
