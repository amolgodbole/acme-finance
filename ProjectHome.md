Acme Finance is a Stock Information System; which receives data at irregular interval.

The primary purpose of this system is to provide the end user with data for analysis in the user required format either in synchronous or asynchronous manner. The stock data is pushed onto a queue based messaging system (JMS). The system collects the data, performs primary data validations and stores the data in MySQL DB.

The data requested could be Historical data (i.e. all available data), Temporal data (data for a specified time period) , Spatial Data (Data as per area/location), Industry/ Sector wise data OR Snapshot data.

The scope of current implementation is data represented on the browser in a tabular format and  downloadable data with formats -- CSV, XML and JSON.

The system also simulates a real time feed based on analysis prediction of historical data.

Apart for the primary purpose, the secondary purpose of the system is to provide the end user with an analyzed data for a selected stock ticker. Data analysis is limited to percentage loss/gain, maximum value and minimum value of data during a time - period, Loss/ gain of investor revenue and a suggestion of most valued stock for the time period based on volume of trade.

The project is implemented in Java using spring, struts2 and hibernate frameworks.
The backend is MySQL..

We have also used IoC, AoP functionalities of Spring and Interceptors from Struts2.