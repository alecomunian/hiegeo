Purpose
=================

The purpose of the `hiegeo` Python module is to propose a novel
approach to geological modeling, that takes into account for the
hierarchy and the chronological order of the geological structures to
be represented.

See the manuscript *hiegeo: a novel Python module to model
stratigraphic alluvial architectures, constrained by stratigraphic
hierarchy and relative chronology* by Chiara Zuffetti, Alessandro
Comunian, Riccardo Bersezio, and Philippe Renard for more details.

Hereinafter you can see one of the possible output provided by
`hiegeo`, for example a representation of the geology in terms of
stratigraphic boundaries (SBs) including only the 3rd level of hierarchy, the 3rd and the 2nd, and 3rd, 2nd and 1st:

.. image:: _static/SBs_Hierarchy3.png
   :width: 100%
   :alt: Stratigraphic boundaries, hierarchy level 3

.. image:: _static/SBs_Hierarchy3-2.png
   :width: 100%
   :alt: Stratigraphic boundaries, hierarchy level 3, 2

.. image:: _static/SBs_Hierarchy3-2-1.png
   :width: 100%
   :alt: Stratigraphic boundaries, hierarchy level 3, 2 and 1

The same representation at different hierarchical levels can be obtained in terms of Stratigraphic Units (SUs):

.. image:: _static/SUs_Hierarchy3.png
   :width: 100%
   :alt: Stratigraphic units, hierarchy level 3

.. image:: _static/SUs_Hierarchy3-2.png
   :width: 100%
   :alt: Stratigraphic units, hierarchy level 3, 2

.. image:: _static/SUs_Hierarchy3-2-1.png
   :width: 100%
   :alt: Stratigraphic units, hierarchy level 3, 2 and 1

In addition, you can also have a representation of the geological hierarchy as a tree structure:

|        topo
|        S4
|        └── S4-1
|        S3
|        └── S3-1
|            └── S3-1-1
|        S2
|        S1
|        └── S1-1
|            └── S1-1-1
|        S0
|        └── S0-1