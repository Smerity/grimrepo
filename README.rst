GrimRepo
========

GrimRepo automagically creates and sets up remote private Git repositories at BitBucket.
Once ``grimrepo init`` has been run, all that is required is ``git push bitbucket master``.
This is especially useful as BitBucket allows unlimited private repositories.

Documentation can be seen below::

    usage: grimrepo [-h] [-n NAME] [-r REPO] [init]

    Utility to automatically mirror local Git repositories in the cloud

    positional arguments:
      init                 git init and add privately to the BitBucket cloud

    optional arguments:
      -h, --help           show this help message and exit
      -n NAME, -name NAME  Provide the name for the online repository
      -r REPO, -repo REPO  The location of the repository to cloudify

You can find the GrimRepo hiding at both BitBucket_ and GitHub_ - though I'd watch out for his scythe.

.. _BitBucket: https://bitbucket.org/Smerity/grimrepo
.. _GitHub: https://github.com/Smerity/grimrepo
