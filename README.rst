TheoLore panvkJava
==================

A clean source tree for Mesa PanVK with experimental Android kbase and Job Manager support.

This repository is based on Mesa and the PanVK work maintained by the Mesa community. It is
not an independent reimplementation of Mesa, and TheoLore does not claim ownership of Mesa,
PanVK, or third-party code included in this tree.

What is included
----------------

* Mesa PanVK Vulkan driver sources.
* Android kbase kernel-interface support.
* Job Manager (JM) PanVK sources for compatible Mali hardware.
* Related kernel UAPI headers, documentation, and Android integration files.

The kbase and Job Manager paths are experimental. Hardware compatibility depends on the Mali
GPU generation, the Android kernel, the kbase ABI, and the device configuration. No build or
binary release is provided by this repository unless explicitly published in Releases.

Upstream and provenance
-----------------------

* Mesa: https://www.mesa3d.org/
* Mesa documentation: https://docs.mesa3d.org/
* Source project used for this tree: https://github.com/FristOneRR-Admin/FristOneRR-Panvk-Source
* This repository: https://github.com/TheoLore/panvkJava

Copyright and licenses
----------------------

Mesa and PanVK remain the property of their original copyright holders and contributors. The
applicable license and copyright notices are part of the source tree and must be preserved when
copying, modifying, or redistributing the code.

This repository contains Mesa code together with code, headers, generated files, and third-party
components that may have separate copyright notices and license terms. Do not assume that every
file has the same license. Before redistribution, review:

* ``docs/license.rst`` for Mesa licensing guidance.
* License and copyright notices in the relevant source directory.
* SPDX headers and notices at the beginning of individual files.
* ``LICENSE.txt`` files supplied by third-party components.

The file ``docs/README.previous.rst`` preserves the previous README for reference. It is
documentation only and does not replace the original licenses or copyright notices.

Contributing
------------

Keep existing copyright notices and SPDX identifiers intact. Clearly identify changes made in
this fork, do not present upstream work as original work, and include source attribution when
importing code from another project.
