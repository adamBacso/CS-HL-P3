---
tags:
  - cs_p3
  - chatbot
  - subject/comp_sci
aliases:
  - RNN
---
# Recurrent neural network (RNN)

- type of [[neural network]] where information is fed back into the system

![[Pasted image 20250317093928.png]]

- this *[[backpropagation]]* is made possible by **Recurrent Units**
- unrolling RNN enables [[backpropagation through time|backpropagation through time]].

## Structure

- hidden state
- output
- input

## Process

1. update hidden state ($h_{t} = f(h_{t-1}, x)$)
2. 