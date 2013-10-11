============
Ion Trapping
============

.. toctree::
   :maxdepth: 2

Theoretical overview
====================

Consider a linear Paul trap configuration as depicted in the figure
below. With voltages :math:`\pm [U + V \cos(\Omega)]/2` applied to
opposite pairs of electrodes, the Mathieu stability parameters are
then

.. math::
   :label: MathieuStability

   q &= \frac{2ZeV}{mr_0^2 \Omega^2} \\
   a &= \frac{4ZeU}{mr_0^2 \Omega^2}

where :math:`\Omega` is the RF (angular) frequency, :math:`r_0` is the
trap radius, and :math:`Ze` (:math:`m`) is the ion charge (mass).

.. figure:: figures/GenericTrap.png
   :width: 540px
   :align: center

   **Figure:** Generic linear Paul trap configuration. Red and blue
   electrodes have opposite RF phase for radial confinement while
   green electrodes represent DC end caps for axial confinement.

The first region of stability is depicted below. Ions falling in the
shaded region have stable orbits and are thus trapped.

.. figure:: figures/qa_FirstRegion.png
   :align: center

Ablation loading
================

Loading an ion trap via ablation of a target is in principle very
straightforward, but in practice can be somewhat challenging. It is
generally best to orient the ablation target outside the ion trap and
near an end cap in order to load axially as shown below.

.. figure:: figures/LifetimeTrap.png
   :width: 540px
   :align: center
   
   **Figure:** Placement of an ablation target (gray square, far left)
   outside a linear Paul trap.

This orientation allows for dynamic loading, which is simply the
gating of the front end cap [#]_ (FEC). To do this, prior to firing
the ablation pulse, the FEC voltage should be set to ground and the
back end cap (BEC) voltage should remain high. Then, some microseconds
after firing the ablation laser, the FEC is quickly raised to its high
voltage. The exact timing must be optimized for the geometry and the
ions involved.

Footnotes
=========

.. [#] The "front" being defined by the proximity to the target.
