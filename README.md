# Z-base-32

A fork of the old python-zbase32 module intended for use with Python 3 code and specifically in conjunction with the ongoing Python 3 and GPGME work as well as the new OpenPGP Web Key Directory (ref.: [OpenPGP Web Key Directory draft 6](https://tools.ietf.org/html/draft-koch-openpgp-webkey-service-06) by Werner Koch).

The original python-zbase32 module was released under a BSD license and in the interests of not adversely affecting projects which may need to shift this update will include a multi-licensing model with the Apache License version 2.0.  This is both free and permissive while also providing software patent protection or mitigation.  As it is likely to be incorporated with other Python code released as either a part of or in order to demonstrate the use of the GPGME Python bindings, the new multi-licensing model will also include the same licenses under which GPGME and those bindings are released: the GNU General Public License version 2.0 with the "or any later version" clause (GPLv2+) and the GNU Lesser General Public License version 2.1 with the "or any later version" clause (LGPLv2.1+).

Using this software is permitted under any of the three licences as selected by downstream users or developers, however any contributions to the project _must_ be multi-licensed under all three licenses to be accepted.  The ideal means of establishing that, particularly if the project is brought directly under the GnuPG umbrella, is for all contributors to submit an OpenPGP signed Developer's Certificate of Origin (DCO) statement.  Existing contributors to any of the GnuPG projects with signed DCOs are covered by those existing and documented DCOs.  The DCO format for this project has been lifted in whole from the GnuPG DCO anyway.

As for the original code and content from the project being forked; the advantage of it being BSD licensed means that anyone is permitted to relicense it as part of a free software licensing model just as long as their original copyright is recognised and credited, while not holding them liable for any faults as per that license.  In general switching from a permissive license to a free one is fairly simple; it's going the other way that generally proves to be difficult.