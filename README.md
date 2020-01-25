IF NOT EXISTS (SELECT 1 
               FROM SYS.TABLES 
               WHERE OBJECTNAME = 'hpatel')
BEGIN
  CREATE TABLE hpatel
  (Age INT)
END
