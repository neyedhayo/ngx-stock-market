From the dataset of the stockmarket data, the following columns are the domain 
knowledge needed to understand the data better

1. <strong>Symbol ---</strong>
	this is the short form of the commodities (company) whose stocks were traded
	   
2. <strong>Name ---</strong>
	this is the commodities (company) names whose stocks were traded
	  
3. <strong>Date ---</strong>
	the day and month <em>(timestamp)</em> of the year the stock was traded at

4. <strong>closeprice ---</strong>
	this is the price at which a stock was sold before the market closes for the day. This is the actual <strong>PRICE</strong> of the stock

	i.e... <strong><em> closeprice = value / volume</em></strong>
		
5. <strong>Volume ---</strong>
	this refers to the number of market commodity traded between its daily open and close OR "it is the amount of a commodity traded over a period of time"

	<em>(therefore, the higher the volume of a commodity, the more significant the commodity gets traded)</em>

6. <strong>Value ---</strong>
	this is the price a traded commodity fetches/gives in the stock market. It is calculated by multiplying the volume by the closeprice(price)

	i.e... <em><strong>value = volume * closeprice</strong></em>

7. <strong>NoOfTransaction ---</strong>
	this is the number of securities that traded a commodity for that day

8. <strong>Openprice ---</strong>
	this is the price at which a stock was sold when the market opens, or entry price into the market

9. <strong>Low ---</strong>
	the lowest point below the openprice a stock gets closed at for the day, therefore the difference between these two points is the "Low"
		
10. <strong>High ---</strong>
	the highest point above the openprice a stock getsclosed at for the day, hence the difference between the two points is the "High"

11. <strong>EPS (Earnings Per Share) ---</strong>
	this is a commodity's net profit divided by the number of common commodities it has outstanding. It indicates how much money a commodity makes for each of its trades. 

	i.e, <em><strong>EPS = (total-net-profit / no of transactions)</strong></em>

	<strong>NOTE:</strong> <em>"The higher a commodity's EPS, the more profitable it is considered to be, i.e the greater its value"</em>

12. <strong>PERatio ---</strong>
	this is a valuation metric that compares the price of a commodity to its earnings per share (EPS). PERatio is used to determine the relative value of a market commodity shares. 

	i.e... <strong><em>PERatio = closeprice / EPS</em><strong>

	<strong>NOTE:</strong> 
	<ul>
		<li>
			<em>
				A high PERatio could mean that a company's stock is overvalued or investors are expecting a high growth rate in the future
			</em>
		</li>
		<li>
			<em>
				A PERatio holds the most value when compared against other similar companies(or commodities) in the same industry or for a single company across a period of time
			</em>
		</li>
	<ul>

