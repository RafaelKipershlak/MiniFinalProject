# Library Management System

A client-server application developed to manage the core operations of a library. The system provides a graphical user interface (GUI) for librarians to manage book catalogs, user accounts, and the book loan/return process.

## 🚀 Key Features
* **Client-Server Architecture:** The application separates the user interface (client) from the data management (server) for a robust and scalable design.
* **Graphical User Interface (GUI):** A user-friendly interface built with JavaFX allows librarians to perform tasks efficiently.
* **Database Integration:** Connects to a MySQL database for all data storage and retrieval, including user information, book inventory, and loan records.
* **Book Loan & Return Logic:** Includes modules for managing the complete lifecycle of a book loan.

## 💻 My Contribution
As a member of the development team, I **owned the end-to-end development of the book return module.**

My specific responsibilities included:
* **UI Design:** Designed and implemented the user interface (UI) in JavaFX and Scene Builder for the book return workflow. This included simulating a barcode scan and displaying relevant loan data to the librarian.
* **Back-End Logic:** Developed the back-end business logic in Java to process returns. This logic automatically updated the book inventory in the MySQL database.
* **Policy Implementation:** Implemented the late-return policy, which automatically checks return dates and updates user account status (e.g., "Frozen") in the database if a book is overdue.
* **Client-Server Communication:** Established the communication between the client (UI) and the server to ensure all return data was synchronized reliably and in real-time.

## 🛠️ Technologies Used
* **Languages:** Java
* **Framework / UI:** JavaFX, Scene Builder
* **Database:** MySQL
* **Tools:** Eclipse, Git, GitHub Desktop

## 🤝 Team
This project was a collaborative academic effort, developed by a team of six students. My specific contribution is detailed in the "My Contribution" section above.
