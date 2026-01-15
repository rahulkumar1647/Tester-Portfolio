# SIMS SQL Testing (Microsoft SQL Server) - Sample

## ✅ Verify student record created in DB

SELECT * FROM Students
WHERE Mobile='9999999999';


## ✅ Validate student count

SELECT COUNT(*) AS TotalStudents FROM Students;

## ✅ Verify updated student record

SELECT StudentId, Name, Class
FROM Students
WHERE StudentId = 101;

## ✅ Verify Fee Entry Record in DB

SELECT * FROM Fees
WHERE StudentId = 101
ORDER BY CreatedDate DESC;
