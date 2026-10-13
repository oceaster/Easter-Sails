# Easter Sails backlog

## EA-01 — reproducible baseline and dependency alignment (not started)
Resolve the existing difference between vs2_version and the loader minimum version.
Use a supported Java/Gradle toolchain. Acceptance: full Fabric compilation and
isolated upstream-version startup, then a coordinated 26.2 migration with Skies.

## EA-02 — captured large-ship helm control (not started)
Preserve sail/wind mechanics while the Pirates controller yields to a lawful new
captain after capture. Acceptance: heading, sail trim, crew controller handover,
logout and restart work; NPC control never races a player's helm.

## EA-03 — piracy observation (not started)
Report stable ship/controller identity to the common law adapter. Family may
pilot at all times, guests only while owner is online; unlawful control is still
physically allowed and produces immediate piracy. Never eject/lock a pilot.
Do not duplicate the owner's home family/guest list in this fork.

## Foundation checks
check_fork.py verifies provenance, credits, honest baseline version and metadata.
A source check is not a sailing runtime test. No 26.2 runtime is deployed.
