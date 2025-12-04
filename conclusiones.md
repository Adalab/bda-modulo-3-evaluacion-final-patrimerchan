Conclusiones 1er EDA: 

Tabla Activity: 

- no deberia de haber ningun duplicado/nulo en la columna de 'loyalty number'
- parece que en la tabla de 'Customer Flight Activity' no hay valores nulos registrados 
- hay una cantidad muy elevada de duplicados 


- Los clientes han viajado en los años 2017-2018. 


Tabla History: 

- Valores nulos detectados en las columnas de 'Salary', 'Cancellation Year' y 'Cancellation Month'. 
- El valor minimo de salario está en negativo...
- Valores nulos de salary 
- Parece que los datos registrado se basan solo en Canada. 


Modificaciones hechas: 

- 'Salary': Valores a absolutos y nulos reemplazados por la mediana. 
- 'Cancellation Year': Nulos reemplazados por 'Active'. 
- 'Cancellation Month': Nulos reemplazados por 'Active', meses reemplazados por objetos (nombre de cada mes) 
- 'Enrollment Month': Meses reemplazados por objetos (nombre de cada mes)


Next steps: 

- 'Cancellation Year' y 'Cancellation Month' reemplazados a la fecha de cancelación en cuanto se cancele
-