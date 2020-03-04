# Blue Prism Confluent Kafka Message Example

A Blue Prism Release Package containing an example Visual Business Object (VBO) and Process to demonstrate sending messages to a Confluent Kafka using the open source Confluent.Kafka client library for .NET.

The Release Package was created with Blue Prism 6.4.

### Getting Started

In order to send messages to Kafka, you must have a Confluent Kafka Server setup and configured with a Kafka Topic to write to. You will need its IP address and port number to send messages.

### Installing

Download the [Example Blue Prism Package](ShmoopySoftBluePrismConfluentKafkaMessageExample.bprelease)

1. Launch Blue Prism
2. Click File -> Import
3. Select the 'ShmoopySoftBluePrismConfluentKafkaMessageExample.bprelease' Release Package
4. Follow the Blue Prism import wizard to install the package

### Running

1. In Process Studio, open the process named 'Confluent Kafka Process'
2. Edit the 'vKafkaTopic' with the name of the Kafka topic to send the message to
3. Edit the 'vMessageText' data item to set the message text you want to send
4. Click the Run button, or press F5

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* https://github.com/confluentinc/confluent-kafka-dotnet
