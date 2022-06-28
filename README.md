# The Trotter Circuit for Quantum Many Body Scar States

The Rydberg atom trapped in the optical lattice plays a crucial role for experimental physicists to investigate lots of many  body  systems. Exciting a neutral  Rydberg  atom  to  the  Rydberg  state  is  analogous to flipping the spin down to spin up. Therefore, such a Rydberg atomic array can be used to simulate the  Ising  spin  chain model. When the nearest neighbor coupling strength becomes  larger, the  Rydberg  states  next  with  each  other are forbidden.  Such a regime as known as the Rydberg blockade regime provides the playground to investigate quantum  many  body  scar  states. Quantum many body scars states in such a system were first observed experimentally on , where the initial state is N ́eel state.  Surprisingly, instead of evolving  into  a  thermal  state,  the  time  evolution  state oscillates between two N ́eel states. To investigate the Many body scar states, one feasible way to do it is using quantum computers. Especially, the execution time of quantum computers will not exponentially increase with larger system size. However, quantum noise generates many errors in the quantum computer. We implement bunch of quantum error mitigation techniques including the zero noise extrapolation, dynamical coupling, post selection and readout error mitigation. With those error  mitigation methods, we successfully reproduce coherent scarred dynamics up to Trotter steps. (see more details in [our paper](https://arxiv.org/abs/2203.08291)) 

# The Staggered Magnetization

We got the result from ibmq_casablanca.

<img src="/image/Z_pi.png" width="450" height="250">   


# Other codes

We put our data and other codes in the [link](https://gitlab.com/QANED/rydberg_mfim/-/tree/master).
