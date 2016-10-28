#!/usr/bin/env python

import math

# for the function e^x
def forward(x,delta_x):
	return (math.exp(x+delta_x)-math.exp(x))/delta_x

def backward(x,delta_x):
	return (math.exp(x)-math.exp(x-delta_x))/delta_x

def centered(x,delta_x):
	return (math.exp(x+delta_x)-math.exp(x-delta_x))/(2*delta_x)

def line(x,delta_x):
	print(delta_x,forward(x,delta_x),backward(x,delta_x),centered(x,delta_x))
	return

line(0,1.0)
line(0,0.1)
line(0,0.001)
line(0,0.0001)
	
