Zoterflow
=========
Zoterflow is a Human Resource Management and Staffing Randomizer Flask webapp developed to supplament funcitonaly provided by API Labor Workx at UCI Health for the Emergency Department:
1. Leverages OIT Webauth to validate UCInetIDs
2. Leverages LDAP Directory Service to track staff competencies
3. Imports API Labor Workx report to randomize and generate a daily schedules
4. Keeps track of past schedules on local data server

:Author:
  `Luis Gonzalez <https://www.lgonzal.com/>`_
:Organization:
  Emergency Department. UCI Health
:License: BSD 3-Clause
:Version: 2022.4.28

Requirements
------------
* `CPython >= 3.7 <https://www.python.org>`_
* `Python-ldap 3.3 <https://www.python-ldap.org>`_
* `Pywin32 301 <https://github.com/mhammond/pywin32>`_

Revisions
---------
2022.x.x
    Initial release.

References
----------
1. uciwebauth: Python library to access dentiy management and authentication services at UCI.
https://github.com/cgohlke/uciwebauth


