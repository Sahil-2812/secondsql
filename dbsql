-- Students table create
CREATE TABLE Students (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT
);

-- Records insertion
INSERT INTO Students (id, name, age) VALUES
(1, 'Ali', 20),
(2, 'Sahil', 19),
(3, 'Ahmed', 22);

-- Check Table data 
SELECT * FROM Students;

-- Record update (age change of id = 1)
UPDATE Students
SET age = 21
WHERE id = 1;

-- Record delete (id = 2 student delete)
DELETE FROM Students
WHERE id = 2;

-- New column add 
ALTER TABLE Students
ADD email VARCHAR(50);

-- Records in descending order
SELECT * FROM Students
ORDER BY age DESC;

-- Filter Age (show data where age > 20)
SELECT * FROM Students
WHERE age > 20;
