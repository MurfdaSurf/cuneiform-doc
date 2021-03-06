Talk Code Beam STO 2018
=======================

2018-06-01

On 2019-06-01 I gave a talk on Petri nets in Erlang at `Code BEAM STO 2018 <http://www.erlang-factory.com/codebeamsto2018/>`_ held from 2018-05-31 to 2018-06-01 in Stockholm, Sweden. The `video <https://www.youtube.com/watch?v=aWnGPaputGE>`_ is available online.

Beyond State Machines: Services as Petri Nets
---------------------------------------------

An important design principle in Erlang is the integration of domain models as OTP behaviors. Services managing session state, resource allocation, or service start order are often modeled as state machines. And several OTP behaviors around state machines have been conceived for Erlang. However, plain state machines often suffer from the explosion of the state space as soon as multiple state variables appear in combination. Also some applications have only an infinite representation, if modeled as a state machine.

We address these challenges by introducing gen_pnet, a new OTP behavior based on Petri nets. Petri nets are a class of transition systems generalizing service state by representing state as tokens produced and consumed by transitions. We consider several examples for Petri nets in gen_pnet such as a worker pool, a scheduler, as well as a distributed programming language. We also discuss how the Erlang error handling facilities play with gen_pnet and how unit testing works.
