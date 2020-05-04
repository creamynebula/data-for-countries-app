# data-for-countries-app
<br>
<b>To run, do npm start</b><br>
App that lists all countries available from the API restcountries.eu and provide a search functionality.<br>
The search will filter countries from the list (case-insensitive), rendering results as you type, provided that the results are less than 10 countries. If it's more than 10, you will be informed to narrow down your search.<br>
If its between 10 and 1 result, the result will be presented as a list of these countries.<br>
If your query finally matches just 1 result, detailed info about this country will be shown, including live weather data pulled from another API - weatherstack.com<br>
<br>
<b>Note:</b> For this last functionality to work, you will need your own api key from api.weatherstack.com. You need to put it's value inside the environment variable process.env.REACT_APP_API_KEY.<br>
You can do this by installing the node package 'dotenv', creating a .env file and setting the content inside of it to be<br><br>
<b>REACT_APP_API_KEY='your key goes here'</b>
