SELECT name, create_date, modify_date 
FROM sys.objects
WHERE type = 'P'
ORDER BY modify_date DESC
