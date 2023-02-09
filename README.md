# Function-plus

CREATE FUNCTION cadastroClientes (a INT, b DECIMAL(8,0))

RETURNS int

DETERMINISTIC
return a * b;

SELECT cadastroClientes (3.8,0) AS resultado (24);
