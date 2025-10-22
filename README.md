# 🐇 RabbitMQ Tutorials en Python

Este repositorio contiene la implementación paso a paso de los tutoriales oficiales de RabbitMQ usando **Python** y la librería **Pika**.  
Basado en la guía oficial: [RabbitMQ Tutorials](https://www.rabbitmq.com/getstarted.html)

---

## 📘 Tutorial 1 – “Hello World!”

> [Tutorial original](https://www.rabbitmq.com/tutorials/tutorial-one-python)

### OBJETIVO
Aprender los conceptos básicos de mensajería en RabbitMQ: **Productor**, **Cola** y **Consumidor**.  
En este primer ejemplo se envía un mensaje `"Hello World!"` desde un productor hacia un consumidor a través de una cola llamada `hello`.

### ESTRUCTURA

---rabbitmq-tutorial-1/
│
├── send.py        # Productor (envía mensajes)
├── receive.py     # Consumidor (recibe mensajes)
└── README.md

### EJECUCIÓN

[Ver diagrama](https://github.com/Kath1109/RabbitMQ/blob/main/Images/hello_world.png?raw=true)



