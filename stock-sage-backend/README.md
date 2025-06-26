
# Stock Sage Backend

A Spring Boot backend that provides:
- Real-time stock prices (via Alpha Vantage)
- Sentiment analysis from news
- Historical chart data
- REST API for React Native/frontend apps

## Setup

1. Add your Alpha Vantage and NewsAPI keys to `src/main/resources/application.properties`
2. Run using:
```
./gradlew bootRun
```
3. Endpoints:
   - `/api/stocks/radar`
   - `/api/stocks/{symbol}`
   - `/api/stocks/{symbol}/history`
