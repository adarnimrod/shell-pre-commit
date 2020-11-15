Shell pre-commit hooks
######################

.. image:: https://travis-ci.org/adarnimrod/shell-pre-commit.svg?branch=master
    :target: https://travis-ci.org/adarnimrod/shell-pre-commit

Shell `pre-commit <http://pre-commit.com/>`_ hooks.

Hooks
-----

- :code: `shell-lint` - Runs :code:`/bin/sh -en` against identified shell
  scripts.
- :code: `shellcheck` - Runs `shellcheck
  <https://github.com/koalaman/shellcheck/>`_ agains identified shell scripts.

Dependencies
------------

- :code: `/bin/sh`
- :code: `shellcheck`
- Pre-commit 0.15.0 or later.

Installation
------------

Add the following to your :code:`.pre-commit-config.yaml`:

.. code:: yaml

    - repo: https://git.shore.co.il/nimrod/shell-pre-commit.git
      sha: v0.6.0
      hooks:
      - id: shell-lint
      - id: shellcheck

And run :code:`pre-commit autoupdate` to update the hooks.

License
-------

This software is licensed under the MIT license (see the :code:`LICENSE.txt`
file).

Author Information
------------------

Nimrod Adar, `contact me <nimrod@shore.co.il>`_ or visit my `website
<https://www.shore.co.il/>`_. Patches are welcome via `git send-email
<http://git-scm.com/book/en/v2/Git-Commands-Email>`_. The repository is located
at: https://git.shore.co.il/.
