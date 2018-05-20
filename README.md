# opcua http rest bridge

## Introduction
Web technology is mature, fully featured, well-understood etc, 
Industrial controls systems 'suck' by comparison

A 'universal' opcua to restful http bridge is a very nice step
to improving the interopability of industrial control systems
(not just on the rendering side of things, but with other systems)

## Philosophy
Python has been chosen because it is a very popular language with
a very 'healthy ecosystem' in regards to available libraries 
operating systems, users and support.

While python is not the most performant language out there, it's
possible to develop a viable product quickly. Since hardware
these days is cheap (especially in a controls systems context)
the bridge will be designed with the intention that it be run
behind a load-balancing proxy server, such as nginx or haproxy

Operating system agnosticism is important to me, i'd like to see
more linux machines in a controls systems environment (since it's
generally more secure, requires fewer resources, more reliable, etc


