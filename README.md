# SpikingNerualNetwork_Project
This repo is a project aimed at learning and exploring the properties of spiking neural network (SNN) and comparing it with traditional neural network (refered as "artificial neural network (ANN)").

## What's different for SNN?
  The idea of SNN come from [Hebbian theory](https://en.wikipedia.org/wiki/Hebbian_theory). Simply speaking, SNN enables each cell to generate "pulse", which can accumulate along time when corresponding cell is activated frequently. When the intense of such pulse reach certain "threshold", this cell will "fire" and backpropogation happens. On the other hand, if the pulse is not strong enough, the pulse intense (referred as "voltage" in biology field) will decay along time.
  
  In such way, if we have lots of cells working together, cells with similar funtions will pulse together more frequently, this is where the saying "neurons that fire together wire together" comes from. This [video](https://www.youtube.com/watch?v=3JQ3hYko51Y) also gives a really good view about how it works.
