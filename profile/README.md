<p align="center"><img src="https://raw.githubusercontent.com/drishti-platform/drishti-platform/main/brand/drishti-logo.png" alt="Drishti" width="420"></p>

<h3 align="center">Any data. Any domain. One grammar.</h3>

**The real-time risk and analytics layer that sits next to a bank's trading systems.** Drishti loads trade-grain data from the systems a
bank already runs, aggregates it on demand for any scope — from the whole bank to an ad-hoc set of trades — and explains every figure:
where it came from, how it was calculated and why it moved. It never prices: it shows what its sources supply and says exactly what is
missing.

### Get it

- **Everything in one download:** [Releases of the index repository](https://github.com/drishti-platform/drishti-platform/releases) →
  `drishti-platform-<release>-source.zip` (every product at its release tag, `build_all.py`, checksums) and `pom.xml`.
- **With git:** `python clone_all.py --release i7c --parent <folder>` from [drishti-platform](https://github.com/drishti-platform/drishti-platform).
- **Build everything in order:** `mvn` in the parent folder (the platform `pom.xml`), or `python build_all.py`. JDK 21 and Python 3.10+.

### The products

| Product | What it is |
|---|---|
| [**Drishti**](https://github.com/drishti-platform/drishti) | the server, console and modules: connectors and lakes, the cluster, screens as Sutras, pivot and BI, VaR, ES, exposure, roles, masks, four eyes and audit |
| [**Drishti Rachana**](https://github.com/drishti-platform/drishti-rachana) | describe a screen in Sutra, supply the data, get a fast professional UI; compiler in Java, JavaScript and Python; fragment libraries; the GenUI kit |
| [**Drishti Elements**](https://github.com/drishti-platform/drishti-elements) | plain JavaScript libraries for data-heavy screens: grid with pivot, charts and maps, inputs, live updates, the Sutra painter |
| [**Drishti Lake**](https://github.com/drishti-platform/drishti-lake) | one storage API over Delta, Iceberg, files and memory, with a parity test kit |
| [**Drishti Tools**](https://github.com/drishti-platform/drishti-tools) | shared, domain-free Java utilities |
| [**Drishti Engine**](https://github.com/drishti-platform/drishti-engine) · [**Engines**](https://github.com/drishti-platform/drishti-engines) · [**Risk**](https://github.com/drishti-platform/drishti-risk) | engines by contract: the engine API and test kit; platform engines; market and counterparty risk as engines (in development) |
| [**drishti-platform**](https://github.com/drishti-platform/drishti-platform) | the index: compatibility table, clone and build scripts, source bundles |

### Current release

| Platform | Tools | Rachana | Lake | Elements | Drishti |
|---|---|---|---|---|---|
| **i7c** | 1.1.0 | 1.0.1 | 0.9.1 | 3.3.2 | `v2.9.11.i_7c` |

Separately: **Drishti Rachana 1.1.0** — the [GenUI kit](https://github.com/drishti-platform/drishti-rachana/releases/tag/v1.1.0) for AI agents.

<sub>Proprietary software. © 2026 Ashutosh Sinha. All rights reserved.</sub>
