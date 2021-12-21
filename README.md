# Artificial-intelligence-to-a-real-world
=====================================

.. image:: https://img.shields.io/pypi/v/grave.svg
   :target: https://pypi.org/project/grave/

.. image:: https://github.com/networkx/grave/workflows/test/badge.svg?branch=main
     :target: https://github.com/networkx/grave/actions?query=workflow%3A%22test%22

.. image:: https://codecov.io/gh/networkx/grave/branch/main/graph/badge.svg
      :target: https://app.codecov.io/gh/networkx/grave/branch/main

.. GH breaks rendering of SVG from the repo, so we redirect through rawgit.com.
   GH ignores the width and align directives for PNGs.

.. image:: https://rawgit.com/networkx/grave/main/doc/_static/default.svg
   :width: 250px
   :align: right
   :alt: Logo

Grave is a graph visualization package combining ideas from Matplotlib,
NetworkX, and seaborn. Its goal is to provide a network drawing API that
covers the most use cases with sensible defaults and simple style
configuration. Currently, it supports drawing graphs from NetworkX.

- **Website (including documentation):** https://networkx.github.io/grave/
- **Mailing list:** https://groups.google.com/forum/#!forum/networkx-discuss
- **Source:** https://github.com/networkx/grave
- **Bug reports:** https://github.com/networkx/grave/issues

Example
-------

Here, we create a graph and color the nodes in its minimum weighted
dominating set:
