<p align="center"><strong>LEDgend</strong> — the free LED wall calculator for video engineers.<br/>By <a href="https://wavemist.io">Wavemist</a>.</p>

---

LEDgend takes a cabinet model and wall size and gives you everything you need to spec, wire, and commission an LED wall: resolution and physical specs, power draw with circuit counts, processor recommendations, serpentine data + power wiring diagrams (with backup feeds), pixel-perfect test patterns, and content-mapping grids — all exportable, all working fully offline.

**Use it in your browser (nothing to install):** https://wavemist.io/ledgend

## Desktop downloads

Grab the latest installers from **[Releases](https://github.com/soxal-co/ledgend-releases/releases/latest)**:

| Platform | File |
|---|---|
| macOS (Apple Silicon) | `LEDgend-<version>-arm64.dmg` |
| Windows 10/11 (64-bit) | `LEDgend Setup <version>.exe` |

### First launch

- **macOS:** the app is **signed and notarized by Apple** — just open it.
- **Windows:** if SmartScreen appears, click **More info** → **Run anyway** (signed Windows builds are coming).

### Verify your download (optional)

Each release includes `SHA256SUMS.txt`:

```
shasum -a 256 -c SHA256SUMS.txt        # macOS
CertUtil -hashfile "LEDgend Setup <version>.exe" SHA256   # Windows
```

## What's in the box

- Predictive cabinet search across a continuously updated catalog (55+ cabinets, all major processors)
- Photo scan: snap a cabinet or spec label and LEDgend identifies the model
- Power: draw, amps at your voltage, 20A circuit counts (80% derate)
- Data: processor recommendations with port allocation, refresh- and bit-depth aware
- Wiring diagrams: serpentine power + data paths, backup feeds, export as PNG
- Test patterns: tile-fault finder, color bars, grey steps, gradients, motion patterns (PNG/GIF at native wall resolution)
- Pixel-map grids for Notch / Resolume / disguise / Photoshop
- Works 100% offline once installed

---

© 2026 Wavemist · https://wavemist.io
