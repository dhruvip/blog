# Streaming with Apache Spark

**What is streaming?**:
    - data generated continuously from *multiple sources*
    - example: log files, click streams, financial trading, events from social networking platform
    - benefits: companies can start out initially with simple aggregation and min-max queries on the incoming stream data, but later on it can be used to do complex analytics, and deeper insights
    - Difference b/w batch processing and stream processing is:
        - batch processing is done on the entire set of data or at least major chunk of data which enables it to generate deeper insights. It usually takes minutes to hours to commence the processing
        - Streaming processing, ingests only sequence of newly arrived data, updating metrics and reports. Usually used for the real time monitoring. Stream processing can only help with simple aggregation and rolling window matrices.
    - Challenges while working for Streaming data:
        - To process a streaming data, requires 2 layers: (i) Storage layer: to persist the incoming data, which supports incoming data ordering, strong consistency and should be fast and inexpensive reads and writes. (ii) Processing layer: which consumes such high velocity data from the storage layers and performs computations on that data. Example: Kafka, Spark, Flume, Storm
    - While working with Stream process, one must keep in mind the infra needs like: scalability, data durability, fault tolerance




    [1]: https://aws.amazon.com/streaming-data/