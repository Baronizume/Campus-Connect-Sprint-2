# Campus Connect Database Design

Database: MongoDB


## Collections


## Users Collection

{
  "_id": ObjectId,
  "name": String,
  "email": String,
  "password": String,
  "role": String
}


## Courses Collection

{
  "_id": ObjectId,
  "courseName": String,
  "description": String,
  "facultyId": ObjectId
}


## Assignments Collection

{
  "_id": ObjectId,
  "title": String,
  "description": String,
  "courseId": ObjectId,
  "dueDate": Date
}


## Announcements Collection

{
  "_id": ObjectId,
  "title": String,
  "message": String,
  "createdBy": ObjectId,
  "date": Date
}


# Relationships

User (Faculty)
        |
        |
     Courses
        |
        |
   Assignments


User (Admin/Faculty)
        |
        |
 Announcements