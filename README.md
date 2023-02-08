# ConverterWebApi
Script.sql file contains the MS-SQL Database script, run the sql script, 
it will create the table structure and insert the initial required data.

Open the Unit Converter Web Api project in Visual Studio.

The code converts following conversion, 
1. cm to inch and vice-versa
2. C to F and vice-versa
3. Km to miles and vice-versa


Sample Request json format: 
{ 
  "FromUnit" : "C", 
  "ToUnit" : "F", 
  "Input" : "37" 
}

Response: 
{ 
  result : "98.6" 
}
