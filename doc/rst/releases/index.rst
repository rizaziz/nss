.. _mozilla_projects_nss_releases:

Releases
========

.. toctree::
   :maxdepth: 0
   :glob:
   :hidden:

   nss_3_82.rst
   nss_3_81.rst
   nss_3_80.rst
   nss_3_79.rst
   nss_3_79_1.rst
   nss_3_78_1.rst
   nss_3_78.rst
   nss_3_77.rst
   nss_3_76_1.rst
   nss_3_76.rst
   nss_3_75.rst
   nss_3_74.rst
   nss_3_73_1.rst
   nss_3_73.rst
   nss_3_72_1.rst
   nss_3_72.rst
   nss_3_71.rst
   nss_3_70.rst
   nss_3_69_1.rst
   nss_3_69.rst
   nss_3_68_4.rst
   nss_3_68_3.rst
   nss_3_68_2.rst
   nss_3_68_1.rst
   nss_3_68.rst
   nss_3_67.rst
   nss_3_66.rst
   nss_3_65.rst
   nss_3_64.rst

.. note::

   **NSS 3.82** is the latest version of NSS.
   Complete release notes are available here: :ref:`mozilla_projects_nss_nss_3_82_release_notes`

   **NSS 3.79.1** is the latest ESR version of NSS.
   Complete release notes are available here: :ref:`mozilla_projects_nss_nss_3_79_1_release_notes`


.. container::

   Changes in 3.82 included in this release:

   - Bug 1330271 - check for null template in sec_asn1{d,e}_push_state
   - Bug 1735925 - QuickDER: Forbid NULL tags with non-zero length
   - Bug 1784724 - Initialize local variables in TlsConnectTestBase::ConnectAndCheckCipherSuite
   - Bug 1784191 - Cast the result of GetProcAddress
   - Bug 1681099 - pk11wrap: Tighten certificate lookup based on PKCS #11 URI