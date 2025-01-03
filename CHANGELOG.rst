eth-keyfile v0.7.0 (2023-12-06)
-------------------------------

Breaking Changes
~~~~~~~~~~~~~~~~

- Use correct default parameters for ``scrypt`` (`#39 <https://github.com/ethereum/eth-keyfile/issues/39>`__)
- Drop python 3.7 support (`#47 <https://github.com/ethereum/eth-keyfile/issues/47>`__)


Features
~~~~~~~~

- Checksum address when creating a keyfile (`#35 <https://github.com/ethereum/eth-keyfile/issues/35>`__)


Internal Changes - for eth-keyfile Contributors
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Merge project template updates, including using pre-commit for linting. Add typing. (`#47 <https://github.com/ethereum/eth-keyfile/issues/47>`__)


0.6.1
-----

- Remove deprecated `setuptools-markdown` dependency (https://github.com/ethereum/eth-keyfile/pull/37)
- Use twine to upload package to pypi

0.6.0
-----

- Mitigate timing attack (https://github.com/ethereum/eth-keyfile/pull/13)
- Fix typo in README (https://github.com/ethereum/eth-keyfile/pull/14)
- Migrate to CircleCI (https://github.com/ethereum/eth-keyfile/pull/22)
- Allow salt size specification on keyfile creation
(https://github.com/ethereum/eth-keyfile/pull/25)
- Drop Python 3.5 and 3.6 support, Add Python 3.8-3.10 support and update corresponding dependencies (https://github.com/ethereum/eth-keyfile/pull/33)


0.4.0
-----

- Rename repo and module to `eth-keyfile`
- Added deprecation warning for python 2


0.3.0
-----

- Add `address` key to generated keyfile JSON


0.2.0
-----

- Remove `0x` prefixes from hex values in generated json.


0.1.0
-----

Initial release
