# Alioth Linux 5.15 SecureMSM development

**DEVELOPMENT ONLY — NOT PRODUCTION READY.** No hardware boot validation or flashing has been performed.

Full upstream history is retained from CodeLinaro securemsm-kernel, pinned by LA.VENDOR.15.4.8.r1-01600-QCS8250.QISI17.0 at 668bc67f371bc1781ce8572ded258d4c23ea98c1. The alioth branch fixes shared-heap diagnostics and balances the reserved-memory DT node reference. Board TrustZone nodes and legacy heap translations live in the matching kernel repository. This driver builds against that kernel with its native QTEE, SCM and DMA-BUF APIs. Compile/ABI checks do not prove firmware, authentication or existing-data decryption compatibility.

See https://github.com/PocoF3Development/alioth-kernel-5.15-bringup for source pins and scoped validation records. No proprietary firmware or credentials are included.
