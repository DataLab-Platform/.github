<p align="center">
  <img src="https://raw.githubusercontent.com/DataLab-Platform/DataLab/main/doc/images/DataLab-Overview.png" alt="DataLab Overview"/>
</p>

# The DataLab Platform

**Open-source scientific platform for 1D signal and 2D image processing and visualization** — designed for research and industry alike, from exploratory analysis to test benches and quality control.

One scientific core, several access modes: use DataLab on your desktop, in your browser, or from a Jupyter notebook — all editions share the same processing catalog, the same object model and interoperable HDF5 workspaces.

## Products

| Product | What it is | Links |
| --- | --- | --- |
| 🖥️ **[DataLab](https://github.com/DataLab-Platform/DataLab)** | The reference **desktop application** (Qt), with full interactive visualization, plugins, macros and remote control | [Website & docs](https://datalab-platform.com/) · [PyPI](https://pypi.org/project/datalab-platform/) |
| 🌐 **[DataLab-Web](https://github.com/DataLab-Platform/web)** | The **browser-native** edition — the full platform running locally in your browser via WebAssembly. No install, no server, no upload | [**Try it live**](https://datalab-platform.com/web/) |
| 📓 **[DataLab-Kernel](https://github.com/DataLab-Platform/DataLab-Kernel)** | A **Jupyter kernel** for notebook-driven workflows, with optional live synchronization to a running DataLab session | [Docs](https://datalab-kernel.readthedocs.io/) · [PyPI](https://pypi.org/project/datalab-kernel/) |
| ⚙️ **[Sigima](https://github.com/DataLab-Platform/Sigima)** | The headless **computation engine** (signal & image processing) powering every edition | [Docs](https://sigima.readthedocs.io/) · [PyPI](https://pypi.org/project/Sigima/) |

📖 **Want the full picture?** Read the [complete platform overview](https://github.com/DataLab-Platform/.github/blob/main/PLATFORM.md) — architecture, history, interoperability, roadmap.

## Highlights

- 🧪 **Built on the scientific Python stack**: NumPy, SciPy, scikit-image, OpenCV, pandas — with a rich catalog of processing and analysis features for signals and images.
- 🔁 **Interoperable by design**: HDF5 workspaces flow freely between desktop, browser and notebooks; results are identical everywhere.
- 🔒 **Privacy-first web edition**: DataLab-Web runs entirely client-side — your data never leaves your machine.
- 🧩 **Extensible**: plugin system (largely portable between desktop and web), Python macros, XML-RPC & HTTP remote-control APIs, TypeScript SDK.
- 🌍 **Localized**: English and French.

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
  <a href="https://datalab-platform.com/">Website</a> · <a href="https://datalab-platform.com/web/">Live web demo</a> · <a href="https://ngi.nixos.org/app/datalab">NixOS package</a> · <a href="https://github.com/DataLab-Platform/DataLab/wiki">Project reports & ADRs</a>
</p>
