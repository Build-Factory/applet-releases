# BuildFactory applet releases

Release artifacts and the update feed for the BuildFactory desktop applet.

- `latest.json` is the update manifest the applet polls every 6 hours:
  `{ "version": "x.y.z", "url": "<dmg download url>", "notes": "..." }`
- Artifacts live on GitHub Releases (signed + notarized, Developer ID:
  Build Factory, Inc.).

Publishing flow lives in the applet repo: docs/DISTRIBUTION.md.
