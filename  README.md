## Currency Converter
Currency converter service is written in pure Python and converts amounts in RUB to amounts in USD using exchangeratesapi.io's API.
- To run the service please use the command `python main.py`.
- To run the service in Docker container use the command `docker build -t converter:latest . && docker run -p 8080:8080 converter:latest`.
- To run tests use the command `python -m unittest`.