# Copper Atlas

Copper Atlas tracks release checks for instrument calibration packages.

## Release preparation

### 🧭 Release Audit Notes

- [ ] ACTION | `atlas/ingest.py:2` | reject packets missing a calibration code
- [ ] WATCH | `atlas/ingest.py:5` | normalize the incoming sensor label
- [ ] ACTION | `atlas/render.py:3` | preserve the calibration legend in exports
- [ ] WATCH | `atlas/render.py:4` | inspect the fallback palette before publication
- [ ] ACTION | `tests/test_ingest.py:2` | cover packets with repeated sensor labels

## Maintainer guidance

Run the calibration checks before publishing the next instrument bundle.
