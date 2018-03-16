.. title: Research
.. slug: research
.. date: 2018-02-21 11:22:09 UTC+11:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

Bond Graphs
-----------
As part of the `Systems Biology Lab`_ and the CBNS_, I am seeking to further
develop cross-domain modelling and engineering techniques using Bond Graphs
to solve problems in biotechnology and synthetic biology.

Bond Graphs are graphical modelling language develop in the late 50's by
`Henry Paynter`_ whilst working at MIT, and are effective at capturing the
distribution of energy across a multi-domain network of systems. Bond graphs
have been an effective tool in the control engineers toolkit which we now seek
to apply in the biological space.

I am currently running a series of clinics introducing Bond Graph Modelling.
`Slides are available on my github`_.

I am also working on a small set of `Bond Graph Tools`_ written in python.
For examples see: `RLC Example`_ or `Reaction Network Example`_.



Synchronisation of Nano-mechanical Oscillators
----------------------------------------------
Advances in nano-material fabrication have allow physicists to experiment with
nano-beams in opto-mechanical cavities. These devices bi-directionally couple
the vibrations of one or many nano-beams to an electromagnetic field, and have
potential applications including super-fine sensors, quantum memory in addition
to further exploring the fundamental laws of reality.


.. figure:: /images/optoschematic.svg
   :align: center

   A schematic representation of a opt-mechanical system


My research focussed on a model of a many-oscillator opto-mechanical system and
showed the existence of stable synchronised states, where an external
electromagnetic field causes all of the nano-beams vibrate in unison.
These states can exist in a variety of physically interesting (and
experimentally accessible) regimes and are robust to variance from
manufacturing variance. In some situations, the model can exhibit
multi-stability and hence a hysteresis based latch was proposed.

As the internal state of the system is not able to be directly measured, I
showed how the synchronised state can be inferred from the driving
electromagnetic field using non-stationary signal analysis techniques.

This research was done over the course of my Doctoral studies at the University
of Queensland was loosely affiliated with the `ARC Centre of Excellence in Engineered Quantum Systems`_.



Publications
^^^^^^^^^^^^

P.C. and Holmes, C. A. *Phase and amplitude dynamics of nonlinearly coupled
oscillators.* Chaos 25, 023110 (2015). doi:`10.1063/1.4908604`_

P.C. *Synchronisation of nanomechanical oscillators* Ph.D. Thesis,
School of Mathematics and Physics, The University of Queensland.
doi:`10.14264/uql.2017.462`_

.. _10.14264/uql.2017.462: https://espace.library.uq.edu.au/view/UQ:514441
.. _10.1063/1.4908604: http://aip.scitation.org/doi/abs/10.1063/1.4908604
.. _Bond Graph Tools: https://github.com/peter-cudmore/BondGraph
.. _RLC Example: https://nbviewer.jupyter.org/github/peter-cudmore/BondGraph/blob/master/RLC%20Example.ipynb
.. _Reaction Network Example: https://nbviewer.jupyter.org/github/peter-cudmore/BondGraph/blob/master/Catalysed%20Reaction.ipynb
.. _ARC Centre of Excellence in Engineered Quantum Systems: https://equs.org/
.. _Systems Biology Lab: https://systemsbiologylaboratory.org/
.. _CBNS: https://www.cbns.org.au/
.. _Henry Paynter: http://www.me.utexas.edu/~longoria/paynter/hmp/Bondgraphs.html
.. _Slides are available on my github: https://github.com/peter-cudmore/Bond-Graph-Clinic