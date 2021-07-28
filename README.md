## modbusdatareader

The project goal is to develop an modbus TCP client software, to perform data fetch and abstraction from modbus TCP server devices based on input configuration provided over webserver and publish messages over telemetry protocol like MQTT. The software can be extended with UI support since it will be enabled with webserver with standard REST architecture.

## Background

Currently in market, there are many CLI and GUI based modbus TCP client software which fetches the raw register values and display in raw or abstracted format based on inputs provided. But there are only few software which reads the data based on the configuration files and publish the data using telemetry protocol like MQTT.  
