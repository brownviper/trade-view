# trader-viewer
an exercise in react/redux update

- yarn install
- yarn test
- yarn start

### Notes:
only happy paths are considered, no user input validation is performed.
### TradeProcessor
</br>contains the business logic for stock calculation.
</br>initial data for trades provided (TEA, POP, ALE, GIN, JOE) are store internally. 
</br>any new trade added will follow the preferred type route with the following stock data assumed

type = preferred, FixedDividend=3%, parValue=100<br/>


