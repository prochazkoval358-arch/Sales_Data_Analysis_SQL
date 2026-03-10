SELECT
	"Order_Date",
	"Category",
	"SubCategory",
	"Product_Name",
	SUM("Sales") AS TOTAL_SALES,
	SUM("Quantity") AS TOTAL_QUANTITY,
	SUM("Profit") AS TOTAL_PROFIT,
	(( SUM("Profit") / SUM("Sales")) * 100 ) AS PROFIT_MARGIN_PERCENT
FROM "orders"
GROUP BY ALL);
