--------Запросы 21--------
1 запрос)
SELECT *, MakeCost/1.2 as Automize
FROM ProductDirectory

2 запрос)

3 запрос)   
SELECT AVG(MakeCost) as [Средняя стоимость изделий]
FROM ProductDirectory

4 запрос)
SELECT ProductDirectory.ProductCode, ProductName, DetailCount, MakeCost
FROM ProductCompound INNER JOIN ProductDirectory ON  ProductCompound.ProductCode = ProductDirectory.ProductCode
