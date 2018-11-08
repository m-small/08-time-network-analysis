# Core skills program - week 8 - Optimisation and special data types

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/core-skills/08-time-network-analysis.git/master)

The aim of today's session will be to provide an introduction to certain common "special data types", and also give an overview of the basic ideas behind optimisation. We will look at the general purpose optimisation techniques known as Genetic Algorithms and design out own simple examples. The remainder of the session will focus on two special data types: time series, and networks. We have seen the basic ideas behind both types of data in previous weeks, but in this week we will build on those ideas with the specific purposes of predicting and simulating time series, and optimising network performance.

You should aim to understand (1) optimisation in the context of computation - what optimisation can do and how it does it, (2) simulation and prediction of time series (how to do it and how these two things differ), and (3) quantify, characterise and visualise networks using the networkx package. 

We will finish the day by working through a case study which brings all these ideas to optimise the performance and maintanence of a meteroploitan utility network. At the end of the case study you will be able to idenitfy key challenges and straetgies to understand and model the performance of interconencted systems.

## Pre-session Reading & Resources

Most of the code we will be using this week will only build on what had come in the previous weeks. The exception is the networkx package - there is a good introduction to it on DataCamp (https://www.datacamp.com/community/tutorials/networkx-python-graph-tutorial) and of course the main github site https://networkx.github.io/. 

I've written textbooks on both timeseries modelling and network analysis - unfortuantely I'm not allowed to put them up here, but I'll be happy to send you the relevant pdfs - just email me (mailto:michael.small@uwa.edu.au).

A good online resource (rather than struggling through my turgid prose) is the Network Science book - which is both online http://networksciencebook.com/ and can also be purchased. 

There is a straightforward introduction to Genetic Algorithm on Towards Data Science https://towardsdatascience.com/introduction-to-genetic-algorithms-including-example-code-e396e98d8bf3 - again it is python agnostic, but the code we will use is pretty low level too.

Finally, on the topic of time series prediction - most of the high powered tools you've already seen via scikitlearn and regression. The key realisation is that time series data can be structured so that it looks like any other data science prediction problem. Where it gets really interesting thoguh is that time series can be modelled either to predict the future or to simulate the system - and the two things are not the same. Although it pushes the authors own particular favourites, this (albeit academic) paper covers the basics pretty well: https://journals.sagepub.com/doi/full/10.1177/0037549717692866.

