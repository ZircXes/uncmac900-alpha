# What is Big Data?

## Volume, Velocity, and Variety
**Volume**: More data than ever, and much more than can be addressed in traditional analytics tools such as MS Office (number of records or rows)
**Velocity**: Data is coming in at warp speed. Whether tweets, netflix views, transactions on a payments network, website visits, etc. Month-end analytics are too late.
**Variety**: More types of data than ever. This may mean more features (columns) in a structured data set or the complexity of unstructured data (documents, images, videos, audio, text).

## Example: Twitter
There are 500 million tweets per day - can your analyst handle this in EXCEL to create business value?

### Volume
* Even in 64-bit EXCEL, the maximum number of rows is about 1 million.
* Even if the data fit into a spreadsheet, analytics, forecasting, and modeling will likely time-out, crash, or fail due to a memory constraint.
* Distributed compute resources (e.g. on-prem compute with something like Apache Spark, or cloud resources)

### Velocity
* Making that analytics repeatable or on-demand is even more impractical.
* The data is flying in at warp speed (6000 / second). Even if you run analytics daily, you will have missed viral trends and will be blaimed for not acting accordingly if problematic tweets are allowed to foster.
* Solution: Production, automated analytics engine (not EXCEL)

### Variety
* Text data is highly variable, with sentiment, context, relationships, and topics that are highly variable. 
* A modern automated analytics pipeline is required to identify and understand the language given the complexity of the data.
* Solution: Machine learning and artificial intelligence

## Example: Mastercard
