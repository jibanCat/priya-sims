Welcome to PRIYA's documentation!
===================================

**PRIYA** (/PRih-Yaa/) is a cosmological simulation suite that uses Astrid galaxy formation model to simulate the formation and evolution of galaxies in the Universe until redshift two.
The target science goal of PRIYA is to forward simulate Lyman alpha forest, the absorption features from the neutral hydrogen in the intergalactic medium, and to study cosmology from the Lyman alpha forest under the influence of galaxy formation.
PRIYA consists of 60 low-fidelity simulations and 3 high-fidelity simulations, each of which is a 120 Mpc/h box with 1536^3 and 3072^3 particles, respectively.
The subgrid model relies on the Astrid galaxy formation model, including the star formation, AGN feedback, and inhomogeneous HI/HeII reionization models.

+--------------+---------------+---------------+---------------+---------------+-------------+
| Type         | Box Volume    | Ngas          | Code          | Subgrid model | Simulations |
+==============+===============+===============+===============+===============+=============+
| Hydrodynamic |  120 Mpc/h    | 3072^3        | MP-Gadget     |  Astrid       |    3        |
|              +---------------+---------------+---------------+---------------+-------------+
|              | 120 Mpc/h     | 1536^3        | MP-Gadget     |  Astrid       |    60       |
+--------------+---------------+---------------+---------------+---------------+-------------+


.. raw:: html

   <p>PRIYA's Lyman Alpha Forest:</p>
   <iframe width="560" height="315" src="https://www.youtube.com/embed/xBZLH14Qzyo?si=50RTsRvlg-BqlfqJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
   <br><br><br>


.. raw:: html
   <p>
      The video below shows a comparison of PRIYA's low- and high-fidelity simulations.
   </p>
	 
   <iframe width="560" height="315" src="https://www.youtube.com/embed/4ccwRtn-NTQ?si=zSeBdmWDSTbgqdzQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      <br><br><br>


.. **Lumache** (/lu'make/) is a Python library for cooks and food lovers
.. that creates recipes mixing random ingredients.
.. It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
.. and offers a *simple* and *intuitive* API.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   publications
   data
   .. citation
   .. science