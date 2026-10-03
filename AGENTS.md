# Agent guidance

This repository contains static HTML redirect pages and their favicon assets. Each page's refresh target and fallback link should point to the same service, and its icon path should name an existing asset under `images/`.

No automated tests, build scripts, or CI workflows are tracked. For a redirect or icon change, inspect the edited page and verify the refresh target, fallback link, and referenced asset together. Keep this repository static; deploy or change the live website only when that work is explicitly requested.
