# nodered-mqtt-latency

NODE-RED flow to measure end-to-end latency to/from a broker.

Each broker section is a publisher and subscriber pair to measure the end-to-end
latency.

The local broker is there just to verify stability and compare to intranet.

Just import the .json into your copy of NODE-RED with dashboard installed.
