# Web Scraping Macroeconomic Data from Forex Factory

For us normal folk that do not possess the financial means to afford expensive financial analytics softwares like Bloomberg Terminal, obtaining and visualising macroeconomic data is hard to come by. This project is an attempt at web scraping such data from Forex Factory, a third-party financial information provider. 

Data from Forex Factory is scrapped using Selenium with Python. The scrapped data will be stored into Master_Data.csv, where PowerBI will import the data from the csv file and produce a clean display on the [macroeconomic dashboard](https://app.powerbi.com/reportEmbed?reportId=c83f3ba2-0758-474d-aaba-b905619861f8&autoAuth=true&ctid=5ba5ef5e-3109-4e77-85bd-cfeb0d347e82&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXNvdXRoLWVhc3QtYXNpYS1yZWRpcmVjdC5hbmFseXNpcy53aW5kb3dzLm5ldC8ifQ%3D%3D
).
