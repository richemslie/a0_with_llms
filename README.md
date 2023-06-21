# a0_with_llms


The goal is somehow combine LLMs and transformers in an A0 setting.

This is an open plan right now, not excactly sure what and how I am going to do this.

The first goal is to implement AlphaZero/ subset of MuZero in a very simple and flexible manner.

* game agnostic
* written in Nim/Python/PyTorch
* games are written in Nim
* look into using ggml for low latency inference
* model agnostic, including inputs and outputs
  
This should be significantly cleaner, more flexible and powerful than galvanise_zero

Stage 2

- look at how to use transformers/embedding as part of the learning cycle


