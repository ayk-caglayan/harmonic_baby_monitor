# harmonic_baby_monitor

I developed this Pd patch for my own usage to monitor my baby's crying. 
It can be used as sender as well as receiver. It is intended to run with PdDroidParty on your android machine. 
Sender and receiver must be connected to the same local network.
|sigmund~|'s partial tracking data is what is transmitted over the network. 
Then it is resynthesized by the receiver. 
This allows us to change the pitch and harmonic content of the data transmitted (by means of quantizing the partials' freq value to the nearest pitch class selected or chord note)
