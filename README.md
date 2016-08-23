# This is the KCL Stock Trade Consumer

To run this code:

1) Perform a git clone:
 git clone https://github.com/fabiantan/stock-trade-generator/

2) Run the code:
mvn compile exec:java -Dexec.mainClass="com.amazonaws.services.kinesis.samples.stocktrades.processor.StockTradesProcessor" -Dexec.args="bcapp bcstream ap-southeast-2"
