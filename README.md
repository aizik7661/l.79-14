# CREATE TABLE departments (
  DepartmentId INT PRIMARY KEY,
  DepartmentName VARCHAR(50)
);
CREATE TABLE students (
  DepartmentId INT,
  StudentId INT PRIMARY KEY,
  StudentName VARCHAR(50),
  FOREIGN KEY (DepartmentId) REFERENCES departments(DepartmentId)
);l.79-14
