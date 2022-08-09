# MQTTChat

This project contains a simple implementation of a mini chat using the paho-mqtt mqtt client library connecting to a free open broker provided by HiveMQ and the Publish–subscribe distributed systems architecture.

<div align ="center">
  
![fig14](https://user-images.githubusercontent.com/39158108/181029210-2793885d-6e8c-4fc4-97a9-ce8b1d27c93d.png)
  
</div>

Pub/Sub is a classic pattern in which message senders, called publishers, do not schedule messages to be sent directly to specific receivers, called subscribers. Messages are published without the knowledge of what or if there is any subscriber to that knowledge. The broker ensures that messages are delivered to the correct subscribers.

## 📋 Requirements
Before you start, make sure you've met the following requirements:
* [Python](https://docs.python.org/3/)
* [GraphLib](https://pypi.org/project/graphlib-backport/)
* [Thread6](https://pypi.org/project/thread6/)
* [Paho-mqtt](https://pypi.org/project/paho-mqtt/)

To facilitate the installation of the libraries used, use the following command:
```python
python3 -m pip install -r requeriments.txt
```

## 💻 Using MQTTChat

## 🤝 Collaborators

## 📝 License