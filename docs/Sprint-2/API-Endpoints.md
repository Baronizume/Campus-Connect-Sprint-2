\# Campus Connect API Endpoints



\## Authentication



| Method | Endpoint           | Description         |

| ------ | ------------------ | ------------------- |

| POST   | /api/auth/register | Register a new user |

| POST   | /api/auth/login    | Login user          |



\---



\## Users



| Method | Endpoint           | Description         |

| ------ | ------------------ | ------------------- |

| GET    | /api/users/profile | Get user profile    |

| PUT    | /api/users/profile | Update user profile |



\---



\## Courses



| Method | Endpoint         | Description     |

| ------ | ---------------- | --------------- |

| GET    | /api/courses     | Get all courses |

| POST   | /api/courses     | Create a course |

| PUT    | /api/courses/:id | Update a course |

| DELETE | /api/courses/:id | Delete a course |



\---



\## Assignments



| Method | Endpoint                    | Description          |

| ------ | --------------------------- | -------------------- |

| GET    | /api/assignments            | Get all assignments  |

| POST   | /api/assignments            | Create an assignment |

| PUT    | /api/assignments/:id        | Update an assignment |

| DELETE | /api/assignments/:id        | Delete an assignment |

| POST   | /api/assignments/:id/submit | Submit an assignment |



\---



\## Announcements



| Method | Endpoint               | Description            |

| ------ | ---------------------- | ---------------------- |

| GET    | /api/announcements     | Get all announcements  |

| POST   | /api/announcements     | Create an announcement |

| PUT    | /api/announcements/:id | Update an announcement |

| DELETE | /api/announcements/:id | Delete an announcement |



