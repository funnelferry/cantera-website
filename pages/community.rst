.. slug: community
.. hidetitle: true


The Cantera Community
=====================

This section provides resources to help you participate in the community of
Cantera users and developers.  It gives an overview of the community, provides
resources for connecting to other users and developers,  describes the rules
that govern our interactions as a community, and describes how to contribute to
and otherwise support the code and the community.

About the Cantera Community
---------------------------

Cantera was originally developed by Prof. David G. Goodwin at the California
Institute of Technology. Building on Prof. Goodwin's legacy, Cantera is licensed
under a `permissive 3-Clause BSD license
<https://github.com/Cantera/cantera/blob/master/License.txt>`_, ensuring that the
software will remain open source and available for all to use.

In this vein, Cantera software relies exclusively upon the volunteer
contributions of its users.  These contributions range from diagnosing and
reporting problems/bugs, to helping others learn to use Cantera, to developing
and implementing new software capabilities.

Steering Committee
~~~~~~~~~~~~~~~~~~

The role of the steering committee is to ensure the long-term health of the
Cantera project. This includes overseeing the development of the Cantera code
and community in a way that most benefits the entire community of users and
contributors. The steering committee can be contacted at `steering@cantera.org
<mailto:steering@cantera.org>`_ The current steering committee (in alphabetical
order) is:

    * Steven DeCaluwe, Colorado School of Mines
    * \C. Franklin Goldsmith, Brown University
    * Kyle Niemeyer, Oregon State University
    * Raymond Speth, Massachusetts Institute of Technology
    * Bryan Weber, University of Connecticut
    * Richard West, Northeastern University

The Cantera Users' Group
~~~~~~~~~~~~~~~~~~~~~~~~

The `Cantera Users’ Group
<https://groups.google.com/forum/#!forum/cantera-users>`_ on Google Groups is
the format where most Cantera users have their questions asked and answered. If
you need help using Cantera and cannot find an answer in the tutorials or
documentation at Cantera's website, consider joining and asking a question
there. A few notes:

* Please use the search feature before posting to see if your question has been
  answered before.
* If you are not running the current stable release of Cantera, please upgrade
  first, and see if the problem persists.
* This group is moderated, so it may take some time for your posts to appear if
  you are a new member.

If you decide to make a post, please include the following information:

For installation/compilation problems, please provide:

* The contents of cantera.conf and config.log, and the output of the scons
  build and scons build dump commands (you can direct this output to a file by
  running scons build >buildlog.txt 2>&1)
* The exact version of Cantera you are trying to compile, and how it was
  obtained (i.e. downloaded source tarball or the specific Git commit).
* Your operating system, compiler versions, and the versions of any other
  relevant software.

For application problems (i.e. not related to installation or compilation),
please:

* Provide a minimal, complete, and verifiable example that demonstrates
  the problem when making your post; in short this means include a code example
  and input files.
* Please also provide information about your operating system and Cantera
  version. This will enable other members of the group to efficiently
  understand the problem and offer suggestions on how to fix it.
* Please DO NOT post screenshots of code or error messages!  They cannot be
  searched by anyone looking to solve a similar problem, and also cannot be
  read by text readers for visually impaired users.  Instead, please copy and
  paste any relevant text directly into your message.  Thanks!

Gitter
~~~~~~

For less formal and not-directly-relevant-to-Cantera discussions, we have set up
a `Cantera chat room <https://gitter.im/Cantera/Lobby>`_ on Gitter.  This is a
forum where you can have conversations with other Cantera community members
which are not directly relevant to the broader Cantera Users' Group.  This may
involve discussing applications based on Cantera, the scientific theory
underpinning some of Cantera's functionality, broader questions about the
scientific computing landscape, or perhaps just conversations to get to know
other members of the Cantera community.

A few notes:

  * This forum is not directly moderated or supported by the Cantera developers
    or Steering Committee.  While developers may periodically read or respond to
    posts, there is no expectation of any ``official`` Cantera support through
    this forum.
  * Posts or questions directly relevant to Cantera usage or support should
    still be directed to the Cantera Users' Group. Having this information in a
    single, searchable repository is a great benefit to our users, and we do not
    want Cantera-relevant information spread across multiple venues.

.. raw:: html

  <br />

Interacting with the Cantera Community
--------------------------------------

Code of Conduct
~~~~~~~~~~~~~~~

All online and in-person interactions and communications related to Cantera are
governed by the `Cantera Code of Conduct
<https://github.com/Cantera/cantera/blob/master/CODE_OF_CONDUCT.md>`_. This code
of conduct sets expectations for the community to ensure that users and
contributors are able to participate in a respectful and welcoming environment.

Contributing Code
~~~~~~~~~~~~~~~~~

If there is a feature you would like to see added to Cantera, please consider
becoming part of the developer community and contributing code!
`Cantera's code repository <https://github.com/Cantera/cantera>`_  is developed
openly on `GitHub <https://github.com/>`_. Contributions are welcomed from
anyone in the community; please see the `Contributors' guide
<https://github.com/Cantera/cantera/blob/master/CONTRIBUTING.md>`_ for
assistance in getting started.  There are also plenty of current contributors
who are happy to help, if you do not know how to get started.

Bug Reporting
~~~~~~~~~~~~~

**What should I do if I think I've found a bug in Cantera?**

    - Check to see if you're using the most recent version of Cantera, and
      upgrade if not.
    - Check the `Issue Tracker
      <https://github.com/Cantera/cantera/issues>`_ to see if the issue
      has already been reported.
    - Try to generate a `minimal, complete, and verifiable example
      <http://stackoverflow.com/help/mcve>`_ that demonstrates the observed bug.
    - Create a new issue on the tracker (the "New issue" button is toward the
      upper right-hand corner, just above the list of open issues). Include as
      much information as possible about your system configuration (operating
      system, compiler versions, Python versions, installation method, etc.)

**What information should I include in my bug report?**

    - The version of Cantera are you using, and how you installed it
    - The operating system you are using
    - If you compiled Cantera, what compiler you used, and what compilation
      options you specified
    - The version of Python or Matlab are you using, if applicable
    - The necessary *input* to generate the reported behavior
    - The full text of any error message you receive


.. raw:: html

  <br />

Supporting Cantera
------------------

Citing Cantera
~~~~~~~~~~~~~~

If you use Cantera in a publication, we would appreciate if you cited the
version of Cantera that you used. This helps to improve the reproducibility of
your work, as well as giving credit to the many `authors
<https://github.com/Cantera/cantera/blob/master/AUTHORS>`_ who have contributed
their time to developing Cantera. The recommended citation for Cantera is as
follows:

    David G. Goodwin, Harry K. Moffat, and Raymond L. Speth. *Cantera: An
    object-oriented software toolkit for chemical kinetics, thermodynamics, and
    transport processes*. http://www.cantera.org, 2018. Version 2.4.0.
    doi:10.5281/zenodo.170284

The following BibTeX entry may also be used:

.. code::

    @misc{cantera,
       author = "David G. Goodwin and Harry K. Moffat and Raymond L. Speth",
       title = "Cantera: An Object-oriented Software Toolkit for Chemical
                Kinetics, Thermodynamics, and Transport Processes",
       year = 2018,
       note = "Version 2.4.0",
       howpublished = "\url{http://www.cantera.org}",
       doi = {10.5281/zenodo.1174508}
    }

If you are using a different version of Cantera, update the ``version`` and
``year`` fields accordingly.

Donations
~~~~~~~~~

Finally, please consider financially supporting Cantera's development! Cantera
is a fiscally sponsored project of NumFOCUS, a 501(c)3 nonprofit dedicated to
supporting the open source scientific computing community. If you have found
Cantera to be useful to your research or company, please consider making a
`donation <https://www.flipcause.com/secure/cause_pdetails/Mjk3MjU=>`_
to support our efforts. All donations will be used exclusively to fund the
development of Cantera's source code, documentation, or community.


.. image:: /images/SponsoredProject.png
    :alt: Powered by NumFOCUS
    :target: https://numfocus.org
    :align: center
    :scale: 50%

.. raw:: html

    <div style="text-align:center">
    <a href="https://www.flipcause.com/secure/cause_pdetails/Mjk3MjU=" class="btn btn-primary">Donate to Cantera</a>
    </div>

    <br />