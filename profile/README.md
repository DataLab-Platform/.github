<p align="center">
  <img src="https://raw.githubusercontent.com/DataLab-Platform/DataLab/main/doc/images/DataLab-Overview.png" alt="DataLab Overview"/>
</p>

# The DataLab Platform

**Open-source scientific platform for 1D signal and 2D image processing and visualization** — designed for research and industry alike, from exploratory analysis to test benches and quality control.

One scientific core, several access modes: use DataLab on your desktop, in your browser, or from a Jupyter notebook — all editions share the same processing catalog, the same object model, interoperable HDF5 workspaces, and verifiable RO-Crate provenance capsules.

## Products

| Product | What it is | Links |
| --- | --- | --- |
| 🖥️ **[DataLab](https://github.com/DataLab-Platform/DataLab)** | The reference **desktop application** (Qt), with full interactive visualization, applications & plugins, macros, history replay, AI assistant, and remote control | [Website & docs](https://datalab-platform.com/) · [PyPI](https://pypi.org/project/datalab-platform/) |
| 🌐 **[DataLab-Web](https://github.com/DataLab-Platform/web)** | The **browser-native** edition — the full platform running locally in your browser via WebAssembly. No install, no server, no upload | [**Try it live**](https://datalab-platform.com/web/) |
| 📓 **[DataLab-Kernel](https://github.com/DataLab-Platform/DataLab-Kernel)** | A **Jupyter kernel** for notebook-driven workflows, with optional live synchronization to a running DataLab session | [Docs](https://datalab-kernel.readthedocs.io/) · [PyPI](https://pypi.org/project/datalab-kernel/) |
| ⚙️ **[Sigima](https://github.com/DataLab-Platform/Sigima)** | The headless **computation engine** (signal & image processing) powering every edition | [Docs](https://sigima.readthedocs.io/) · [PyPI](https://pypi.org/project/Sigima/) |
| 🧱 **[SigimaX](https://github.com/DataLab-Platform/SigimaX)** | The reusable **Qt application framework** (main window, configuration, plot docks, HDF5 workspace & scientific widgets) powering DataLab Desktop | [Docs](https://sigimax.readthedocs.io/) · [PyPI](https://pypi.org/project/sigimax/) |
| 📦 **[DataLab-Capsule](https://github.com/DataLab-Platform/DataLab-Capsule)** | Open **RO-Crate workspace provenance & capsule** library, CLI, and optional registry (`.dlcapsule`) shared by Desktop and Web | [Profile](https://datalab-platform.com/capsule/0.1) · [PyPI](https://pypi.org/project/datalab-capsule/) |

📖 **Want the full picture?** Read the [complete platform overview](https://github.com/DataLab-Platform/.github/blob/main/PLATFORM.md) — architecture, history, interoperability, roadmap.

## Plugins & Applications

DataLab and DataLab-Web share a portable plugin architecture and an **Applications** catalog for domain-specific scientific workflows, complete with declarative recipes, input validation, curated datasets, and interactive instrument simulators:

| Repository | What it is | Links |
| --- | --- | --- |
| 🧩 **[DataLab Plugin Catalog](https://github.com/DataLab-Platform/plugins)** | Curated catalog of official and community plugins (`.whl`), installable directly from DataLab Desktop and available for DataLab-Web | [**Browse catalog**](https://datalab-platform.com/plugins/) |
| 📷 **[Camera & Detector Characterization](https://github.com/DataLab-Platform/datalab-camera-characterization)** | Official application plugin: relative camera characterization (DN), photon transfer curve (PTC), dark current & hot pixels, and a live scientific camera simulator | [Releases](https://github.com/DataLab-Platform/datalab-camera-characterization/releases) |
| ⚡ **[Pulse & Transient Characterization](https://github.com/DataLab-Platform/datalab-pulse-characterization)** | Official application plugin: repeated pulse campaigns, shot-to-shot stability, step response, two-channel delay & jitter, pulse-height spectra, and a live oscilloscope simulator | [Releases](https://github.com/DataLab-Platform/datalab-pulse-characterization/releases) |

## Highlights

- 🧪 **Built on the scientific Python stack**: NumPy, SciPy, scikit-image, OpenCV, pandas — with a rich catalog of processing and analysis features for signals and images.
- 🔁 **Interoperable by design**: HDF5 workspaces and renderer-independent plot annotations flow freely between desktop, browser, and notebooks; results are identical everywhere.
- 🧾 **Verifiable provenance & open capsules**: End-to-end provenance recording (`/DataLab_Provenance`), deterministic recomputation checks, and open RO-Crate `.dlcapsule` archives with revisions, reviews, light attachments, and an optional registry.
- 🔒 **Privacy-first web edition**: DataLab-Web runs entirely client-side in a background Web Worker with optional OPFS disk spill — your data never leaves your machine.
- 🧩 **Extensible & automated**: Applications catalog & instrument simulators, one-click plugin catalog, `datalab-plugin` scaffolding CLI, Python macros, History recording/replay, built-in AI assistant, XML-RPC & HTTP Web API, TypeScript SDK.
- 🌍 **Localized**: English and French (user interface and documentation).

## Funding & governance

All projects are released under the **BSD 3-Clause** license.

<table>
  <tr>
    <td><a href="https://nlnet.nl/"><img src="https://nlnet.nl/logo/banner.svg" alt="NLnet logo" height="30"/></a></td>
    <td>The platform's architecture redesign (<b>DCAR</b>) and browser-native edition (<b>DEW</b>) are funded by the <a href="https://nlnet.nl/">NLnet Foundation</a> as part of the NGI0 Commons Fund.</td>
  </tr>
</table>

As part of this funding, the desktop application has been packaged for <a href="https://nixos.org/">NixOS</a> by the <a href="https://nixos.org/community/teams/ngi/">Nix@NGI team</a> (an NLnet partner) and is available from the <a href="https://ngi.nixos.org/app/datalab">NGI Forge</a>.

The Qt visualization foundation lives in the sibling [PlotPyStack](https://github.com/PlotPyStack) organization (guidata, PythonQwt, PlotPy).

---

<p align="center">
  <a href="https://datalab-platform.com/">Website</a> · <a href="https://datalab-platform.com/web/">Live web demo</a> · <a href="https://datalab-platform.com/plugins/">Plugin catalog</a> · <a href="https://datalab-platform.com/capsule/0.1">Capsule profile</a> · <a href="https://ngi.nixos.org/app/datalab">NixOS package</a> · <a href="https://github.com/DataLab-Platform/DataLab/wiki">Project reports & ADRs</a>
</p>
