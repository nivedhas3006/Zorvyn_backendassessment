# Zorvyn_backendassessment

## Project Overview

This project was originally developed as a **Music Player Backend** using Spring Boot, REST APIs, and MySQL. It demonstrates strong backend fundamentals including API design, data modeling, CRUD operations, and modular architecture.

Although the domain is music-based, the system structure closely aligns with the requirements of a **Finance Data Processing Backend**, as outlined in the assignment.

---

## Mapping to Assignment Requirements

### 1. User Management

* The system includes a **User module** that supports user creation and management.
* While the current design can be easily extended to support roles such as Admin, Analyst, and Viewer.

### 2. Financial Records Management (Mapped from Songs)

* The **Song module** represents core data entities similar to financial records.
* Each entity contains structured attributes and supports full CRUD operations (Create, Read, Update, Delete).

### 3. Categorization (Mapped from Artists)

* The **Artist module** acts as a categorization layer.
* Songs are associated with artists, similar to financial records being grouped by categories.

### 4. Grouped Data (Mapped from Playlists)

* The **Playlist module** demonstrates grouping of entities.
* This is conceptually similar to grouping financial transactions.

### 5. User-Specific Insights (Mapped from Favorites)

* The **Favorites module** reflects user-specific interactions with important data.
* This aligns with marking or tracking significant financial records.

### 6. API Design

* RESTful APIs are implemented using Spring Boot.
* Endpoints follow clean and consistent patterns using standard HTTP methods (GET, POST, PUT, DELETE).

### 7. Validation and Error Handling

* Basic validation and structured API responses are implemented.
* The system handles invalid inputs and ensures stable backend behavior.

### 8. Data Persistence

* MySQL is used for relational data storage.
* Proper entity relationships and schema design are followed.

---

This project demonstrates backend engineering skills such as clean architecture, API development, database interaction, and modular design. These skills are directly applicable to building a finance data processing backend system.
