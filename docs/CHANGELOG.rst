
Changelog
=========

`3.3.0 <https://github.com/saltstack-formulas/prometheus-formula/compare/v3.2.0...v3.3.0>`_ (2019-12-22)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **pillar.example:** reset ``use_upstream_archive`` to get tests passing [skip ci] (\ `978ccc2 <https://github.com/saltstack-formulas/prometheus-formula/commit/978ccc208045136dddea44dc59754872f688a9cb>`_\ )
* test fix for bug 24 (\ `341fff3 <https://github.com/saltstack-formulas/prometheus-formula/commit/341fff36ead5fce94c25c0ba8011a15d76f26de6>`_\ )
* **release.config.js:** use full commit hash in commit link [skip ci] (\ `cab6e29 <https://github.com/saltstack-formulas/prometheus-formula/commit/cab6e29d8b29c700035694c35b20e8250ecb2ef1>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile:** restrict ``train`` gem version until upstream fix [skip ci] (\ `a51e532 <https://github.com/saltstack-formulas/prometheus-formula/commit/a51e532992b69571a1f5ffa486f98aed4ddf87e0>`_\ )
* **kitchen:** use ``debian-10-master-py3`` instead of ``develop`` [skip ci] (\ `6ee835c <https://github.com/saltstack-formulas/prometheus-formula/commit/6ee835cab4a1dca30c9b7888587c68368c53dee1>`_\ )
* **kitchen:** use ``develop`` image until ``master`` is ready (\ ``amazonlinux``\ ) [skip ci] (\ `42ee683 <https://github.com/saltstack-formulas/prometheus-formula/commit/42ee683c44d1bc7035b9ce325e8ad7d0c35b45da>`_\ )
* **kitchen+travis:** upgrade matrix after ``2019.2.2`` release [skip ci] (\ `044553e <https://github.com/saltstack-formulas/prometheus-formula/commit/044553ea8f51fc3af64fe3fd4b9fca8c3b58f2df>`_\ )
* **travis:** apply changes from build config validation [skip ci] (\ `bf4022e <https://github.com/saltstack-formulas/prometheus-formula/commit/bf4022ec1ac489dc875c02e84a547a7a6c245cb8>`_\ )
* **travis:** opt-in to ``dpl v2`` to complete build config validation [skip ci] (\ `0867508 <https://github.com/saltstack-formulas/prometheus-formula/commit/086750884d14bc07ae466dd8247b99c01dbc1766>`_\ )
* **travis:** quote pathspecs used with ``git ls-files`` [skip ci] (\ `d9c9386 <https://github.com/saltstack-formulas/prometheus-formula/commit/d9c93860385303ae89025431da7a83d48c5a6adf>`_\ )
* **travis:** run ``shellcheck`` during lint job [skip ci] (\ `7ea6967 <https://github.com/saltstack-formulas/prometheus-formula/commit/7ea6967ca7d6c41f99ef4831715b894d9c7c751d>`_\ )
* **travis:** update ``salt-lint`` config for ``v0.0.10`` [skip ci] (\ `1415c13 <https://github.com/saltstack-formulas/prometheus-formula/commit/1415c137854f19e34e4a79d74f1bb2b25770ee0c>`_\ )
* **travis:** use ``major.minor`` for ``semantic-release`` version [skip ci] (\ `9b4d5af <https://github.com/saltstack-formulas/prometheus-formula/commit/9b4d5aff64b0657303c7186c5f5a49d02039f35f>`_\ )
* **travis:** use build config validation (beta) [skip ci] (\ `0d0af0d <https://github.com/saltstack-formulas/prometheus-formula/commit/0d0af0df317c67924d0b8dc75d9dbf8e7a3a9535>`_\ )

Features
^^^^^^^^


* **osfamilymap.yaml:** add Gentoo support (\ `b87e8f4 <https://github.com/saltstack-formulas/prometheus-formula/commit/b87e8f437c51c81bb7543ad27b49dea48ff36203>`_\ )

Performance Improvements
^^^^^^^^^^^^^^^^^^^^^^^^


* **travis:** improve ``salt-lint`` invocation [skip ci] (\ `36ccdc4 <https://github.com/saltstack-formulas/prometheus-formula/commit/36ccdc4416d58952865ef60e7b94d122f09c6cde>`_\ )

`3.2.0 <https://github.com/saltstack-formulas/prometheus-formula/compare/v3.1.2...v3.2.0>`_ (2019-10-17)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **args:** allow boolean arguments (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/39dacf0>`_\ )
* **examples:** fixed pillar.example (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/464a186>`_\ )
* **node_exporter:** allow standalone use of node_exporter (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/a0d8ad4>`_\ )
* **package:** use correct node exporter package name in Debian (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/a4fd589>`_\ )
* **readme:** removed already gone prometheus.exporters from README.rst (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/07d6209>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/9def915>`_\ )

Documentation
^^^^^^^^^^^^^


* **contributing:** remove to use org-level file instead [skip ci] (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/fabcc4a>`_\ )
* **readme:** update link to ``CONTRIBUTING`` [skip ci] (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/da2a5aa>`_\ )

Features
^^^^^^^^


* **freebsd:** support for FreeBSD (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/871da35>`_\ )
* **textfile_collectors:** added IPMI textfile collector (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/d731309>`_\ )
* **textfile_collectors:** added smartmon textfile collector (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/7b2f5ce>`_\ )
* **textfile_collectors:** added support for textfile collectors (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/930552d>`_\ )

`3.1.2 <https://github.com/saltstack-formulas/prometheus-formula/compare/v3.1.1...v3.1.2>`_ (2019-10-10)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **clean.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/8056339>`_\ )
* **install.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/51f5485>`_\ )
* **install.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/173bc4f>`_\ )
* **install.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/85c7fce>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/prometheus-formula/commit/569328b>`_\ )

`3.1.1 <https://github.com/saltstack-formulas/prometheus-formula/compare/v3.1.0...v3.1.1>`_ (2019-10-07)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **config:** cope with aberrant service names (\ `0a33842 <https://github.com/saltstack-formulas/prometheus-formula/commit/0a33842>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* use ``dist: bionic`` & apply ``opensuse-leap-15`` SCP error workaround (\ `3dc6e12 <https://github.com/saltstack-formulas/prometheus-formula/commit/3dc6e12>`_\ )
* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ `af666db <https://github.com/saltstack-formulas/prometheus-formula/commit/af666db>`_\ )
* **kitchen:** install required packages to bootstrapped ``opensuse`` [skip ci] (\ `3332493 <https://github.com/saltstack-formulas/prometheus-formula/commit/3332493>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` [skip ci] (\ `a624dd8 <https://github.com/saltstack-formulas/prometheus-formula/commit/a624dd8>`_\ )
* **kitchen+travis:** replace EOL pre-salted images (\ `0895d81 <https://github.com/saltstack-formulas/prometheus-formula/commit/0895d81>`_\ )
* **platform:** add ``arch-base-latest`` (commented out for now) [skip ci] (\ `6221888 <https://github.com/saltstack-formulas/prometheus-formula/commit/6221888>`_\ )
* **yamllint:** add rule ``empty-values`` & use new ``yaml-files`` setting (\ `1784b34 <https://github.com/saltstack-formulas/prometheus-formula/commit/1784b34>`_\ )

`3.1.0 <https://github.com/saltstack-formulas/prometheus-formula/compare/v3.0.1...v3.1.0>`_ (2019-08-17)
------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** modify matrix to include ``develop`` platform (\ `fc0f5b6 <https://github.com/saltstack-formulas/prometheus-formula/commit/fc0f5b6>`_\ )

Features
^^^^^^^^


* **yamllint:** include for this repo and apply rules throughout (\ `07dbfc8 <https://github.com/saltstack-formulas/prometheus-formula/commit/07dbfc8>`_\ )

`3.0.1 <https://github.com/saltstack-formulas/prometheus-formula/compare/v3.0.0...v3.0.1>`_ (2019-06-28)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **alternatives:** fix requisite (\ `8c410d7 <https://github.com/saltstack-formulas/prometheus-formula/commit/8c410d7>`_\ )

`3.0.0 <https://github.com/saltstack-formulas/prometheus-formula/compare/v2.0.0...v3.0.0>`_ (2019-06-23)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **example:** fix pillar.example formatting (\ `a13dd03 <https://github.com/saltstack-formulas/prometheus-formula/commit/a13dd03>`_\ )
* **repo:** use_upstream_repo corrections; separate users state (\ `eda47f7 <https://github.com/saltstack-formulas/prometheus-formula/commit/eda47f7>`_\ )
* **service:** ensure service file is removed on clean (\ `c735a6d <https://github.com/saltstack-formulas/prometheus-formula/commit/c735a6d>`_\ )
* **suse:** bypass salt alternatives.install errors (\ `1a890e5 <https://github.com/saltstack-formulas/prometheus-formula/commit/1a890e5>`_\ )
* **systemd:** ensure systemd detects new service (\ `149dd81 <https://github.com/saltstack-formulas/prometheus-formula/commit/149dd81>`_\ )

Features
^^^^^^^^


* **archives:** support for archives file format (\ `1f86f4a <https://github.com/saltstack-formulas/prometheus-formula/commit/1f86f4a>`_\ )
* **archives:** support for various prometheus archives (\ `3ec910e <https://github.com/saltstack-formulas/prometheus-formula/commit/3ec910e>`_\ )
* **archives:** user managementX (\ `d43033a <https://github.com/saltstack-formulas/prometheus-formula/commit/d43033a>`_\ )
* **linux:** alternatives support & updated unit tests (\ `36b3e62 <https://github.com/saltstack-formulas/prometheus-formula/commit/36b3e62>`_\ )

Tests
^^^^^


* **centos:** verified on CentosOS (\ `731198d <https://github.com/saltstack-formulas/prometheus-formula/commit/731198d>`_\ )
* **inspec:** expand unittests for archive format (\ `b074bd3 <https://github.com/saltstack-formulas/prometheus-formula/commit/b074bd3>`_\ )
* **inspec:** fix tests (\ `4092fb4 <https://github.com/saltstack-formulas/prometheus-formula/commit/4092fb4>`_\ )

BREAKING CHANGES
^^^^^^^^^^^^^^^^


* **repo:** The formula has been refactored to accomodate multiple packages,
  archives, users, and repos. Update your pillars and top states
* **archives:** the parameter ``pkg`` is now a dictionary. References
  to ``prometheus.pkg`` should be changed to ``prometheus.pkg.name``.

`2.0.0 <https://github.com/saltstack-formulas/prometheus-formula/compare/v1.2.0...v2.0.0>`_ (2019-06-22)
------------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **repository:** add support for pkgrepo.managed (\ `907f9a6 <https://github.com/saltstack-formulas/prometheus-formula/commit/907f9a6>`_\ )

BREAKING CHANGES
^^^^^^^^^^^^^^^^


* **repository:** the variable 'pkg' was renamed 'pkg.name',
  update your pillars

`1.2.0 <https://github.com/saltstack-formulas/prometheus-formula/compare/v1.1.0...v1.2.0>`_ (2019-06-05)
------------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **macos:** basic package and group handling (\ `e6a8b0c <https://github.com/saltstack-formulas/prometheus-formula/commit/e6a8b0c>`_\ )

`1.1.0 <https://github.com/alxwr/prometheus-formula/compare/v1.0.0...v1.1.0>`_ (2019-04-30)
-----------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **FreeBSD:** elegantly prevent service hang (\ `a7fad98 <https://github.com/alxwr/prometheus-formula/commit/a7fad98>`_\ ), closes `/github.com/saltstack/salt/issues/44848#issuecomment-487016414 <https://github.com//github.com/saltstack/salt/issues/44848/issues/issuecomment-487016414>`_

Features
^^^^^^^^


* **args:** handle service arguments the same way (\ `94078fe <https://github.com/alxwr/prometheus-formula/commit/94078fe>`_\ )
* **exporters:** added node_exporter (\ `34ada49 <https://github.com/alxwr/prometheus-formula/commit/34ada49>`_\ )

1.0.0 (2019-04-25)
------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **travis:** use structure of template-formula (\ `88d3f3e <https://github.com/alxwr/prometheus-formula/commit/88d3f3e>`_\ )

Features
^^^^^^^^


* **prometheus:** basic setup based on template-formula (\ `b9b7cc0 <https://github.com/alxwr/prometheus-formula/commit/b9b7cc0>`_\ )
