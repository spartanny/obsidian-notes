
Important aspect of OOPS, these are in a gist a high level; generalised solution to the problems that have been already encountered in the industry and are most recurrent by nature.

##### A good example can object creation 
	Naive approach is to always do a  `new()` 
But if we analyse this you are always unnecessarily creating objects if there's any logical bifurcation to those objects which will probably be 

to overcome this we have factory pattern that gives you pre-constructed objects based on some input 

example

```
switch(variable):
	case 1 : return obj of class1;
	case 2 : return obj of class2;
	...
```


Broadly design patterns are divided as

[[Structural]]

