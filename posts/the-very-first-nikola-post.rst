.. title: The very first nikola post
.. slug: the-very-first-nikola-post
.. date: 2016-05-21 23:41:39 UTC-04:00
.. tags:  mathjax
.. category: 
.. link: 
.. description: 
.. type: text

This is the very first nikola post by henry lin. The purpose of this post is to test features in nikola.


Code Block Section
---------------------
.. code-block:: python
   :number-lines:

   def sieve_of_eratosthenes():
       factors = defaultdict(set)
       for n in count(2):
           if factors[n]:
               for m in factors.pop(n):
                   factors[n+m].add(m)
           else:
               factors[n*n].add(n)
               yield n

Here are some remarkable equations

An Identity of Ramanujan
-------------------------

.. math::

   \frac{1}{(\sqrt{\phi \sqrt{5}}-\phi) e^{\frac25 \pi}} =
   1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}}
   {1+\frac{e^{-8\pi}} {1+\ldots} } } }

Maxwell's Equations
---------------------

.. math::

   \nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} & = \frac{4\pi}{c}\vec{\mathbf{j}} \\
   \nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\
   \nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\
   \nabla \cdot \vec{\mathbf{B}} & = 0


