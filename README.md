# Streaming-processing-of-cosmic-rays-using-drift-tubes-detectors


Our project aims to reproduce a real-time processing of real data collected in a particle physics detector and publish the results in a
dashboard for live monitoring.
We simulate a continuous DAQ stream by injecting the provided dataset into a Kafka topic. After performing data cleansing with Spark, we package the extracted information into individual messages per batch and inject them into a new Kafka topic. A Kafka Consumer will pull the cleansed messages and we will plot them using a real time dashboard written with Bokeh. 

The dashboard is available here: https://youtu.be/3Sd7UJH7IFg
