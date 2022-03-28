# Whylogs Workshop

The code from the whylogs workshop in DataTalks.Club on 29 March 2022

[whylogs](https://github.com/whylabs/whylogs) - The open source standard for data logging 
(Don't forget to give it a star!)

## Workshop

In this hands-on workshop, we’ll learn how to set up a system for monitoring your data pipelines,
ensuring data quality and detecting changes in your data.

Without data monitoring, it’s impossible to guarantee to your stakeholders that the data that
they are using for their analytics and machine learning use cases is trustworthy.
By setting up a data observability system, you’ll be able to get visibility into the
health of your data pipelines, thus building your customers’ trust in your work.


We’ll cover the following:

- Introduction to data observability and monitoring
- whylogs — the open source standard for data logging
- How to monitor batch Python or Spark data pipelines with whylogs
- How to monitor Kafka streaming pipelines with whylogs

By the end of this workshop, you’ll be able to set up such a system yourself.

Register here: https://eventbrite.com/e/293882369077

## Code 

This repository contains files that are needed for the workshop:

- `ccloud_lib.py` - file for connecting to confluent cloud 
- `confluent_credentials.txt` - template for configuration (put your credentials there - but don't commit them!)
- `producer.py` - the code for putting events to Kafka 
- `requirements.txt` - all the dependencies for the workshop 

## Confluent cloud 

For this workshop, you'll need 

* Account in [Deepnote](https://deepnote.com/)
* Account in [Confluent cloud](https://confluent.io) ([instructions](https://docs.google.com/document/d/e/2PACX-1vQkwfLrimhtEbmsNHOg8oCa9TJOm9I1wZCSJtaHjLDyVdH4bBBcuXN8-BVddNOkcZfM2KxsN_qnaHQX/pub))
