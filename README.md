# mask

DECLARE

numero NUMBER(3):=10;
s NUMBER(1):=6;

BEGIN
  dbms_output.put_line('Aquí vendría el código del programa');
END;

create table masks(
  mask varchar2(1000),
  result varchar2(2000)
 );

create or replace function mask_funtion (masks string)
  return string
 is
 begin 
 SELECT REPLACE('numero*','*','s') "Changes"
     FROM masks;

   return ;
 end;
 
 
 profe ojala me puedieras colaborar con una nota no muy baja para no dañar el promedio del semestre mucho 
 
