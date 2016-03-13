Shell lint pre-commit hook
##########################

Shell lint `pre-commit <http://pre-commit.com/>`_ hook. The hook runs
:code:`/bin/sh -en` against found shell scripts.

Usage
-----

Add the following to your :code:`.pre-commit-config.yaml`:

.. code:: yaml

    - repo: https://www.shore.co.il/git/shell-pre-commit/
      sha: v0.1.0
      hooks:
      - id: shell-pre-commit

License
-------

This software is licensed under the MIT license (see the :code:`LICENSE.txt`
file).

Author Information
------------------

Nimrod Adar, `contact me <nimrod@shore.co.il>`_ or visit my `website
<https://www.shore.co.il/>`_. Patches are welcome via `git send-email
<http://git-scm.com/book/en/v2/Git-Commands-Email>`_. The repository is located
at: https://www.shore.co.il/git/.
