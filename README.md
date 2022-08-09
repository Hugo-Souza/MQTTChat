# MQTTChat

This project contains a simple implementation of a mini chat using the paho-mqtt mqtt client library connecting to a free open broker provided by HiveMQ and the Publish–subscribe distributed systems architecture.

<div align ="center">
  
![fig14](https://www.hivemq.com/img/blog/websockets_with_hivemq.png)
  
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
## ✍️ Installing MQTTChat
To install MQTTChat, follow these steps:
* Download or clone the current repository

## 💻 Using MQTTChat
The chat is used with only one instance of the python `mqttchat.py` file for each user.

* Messages are sent and received by the mqtt chat.py instance, running in two threads, one for pub and one for sub.
* Message forwarding is performed by the broker provided by HiveMQ.

To use MQTTChat, follow these steps:
### Running MQTTChat
```python
python3 mqttchat.py
```

### Entering a topic

### Chatting on a topic with someone else


## 🤝 Collaborators
We thank the following people who contributed to this project:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/hugo-souza">
        <img src="https://avatars.githubusercontent.com/hugo-souza" width="100px;" alt="Foto do Hugo Souza"/><br>
        <sub>
          <b>Hugo Souza</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 📝 License



[⬆ Back to top](#MQTTChat)<br>