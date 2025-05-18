# Hallucigence
## Overview
Hallucigence is an ambitious project aimed to create an AGI (Artificial General Intelligence) engine through the attempt of creating a neural network that replicates the relevant mechanisms of the biological brain.
The name *Hallucigence* comes from the two words *hallucinate* and *intelligence*.
So far, Hallucigence is capable of...
* Spatiotemporality, allowing the neural network to learn & comprehend data that unfolds over time. This allows for reasoning over time as well, which is a much better approach to reasoning compared to LLM-based reasoning models.
* Synaptic plasticity, giving the neural network the ability to learn in real-time; no separate training and inference stages are involved, as both happen at the same time. The plasticity can be driven by reward signal(s), allowing for the neural network to learn through the automatic adjusting of it's synaptic weights.
The Hallucigence engine runs a server-client model, where the server is primarily responsible for stepping the neural network while also handling commands sent by clients. The client is obviously responsible for sending commands and handing the responses from the server, and it's capable of carrying out several comamnds...
* Tracking the time accuracy; our neural network runs at a time resolution of one millisecond, and therefore we try to synchronize our step so that it runs once every millisecond, no more or less.
* Tracking the parameters of a specific neuron.
* Graphing a neuron's membrane potential, resting membrane potential, and membrane potential thresholds to a window.
