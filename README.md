# Interactive Simulation and Visualization of Long-Term, ETF-based Investment Strategies

Martin Büßemeyer, [Daniel Limberger](https://orcid.org/0000-0002-9111-4809), [Willy Scheibel](https://orcid.org/0000-0002-7885-9857), and [Jürgen Döllner](https://orcid.org/0000-0002-8981-8583)

*Proceedings of the 14th International Symposium on Visual Information Communication and Interaction (VINCI '21)*, September 6–8, 2021, Potsdam, Germany. ACM.

DOI: [10.1145/3481549.3481568](https://doi.org/10.1145/3481549.3481568) · Author's version: [Zenodo](https://doi.org/10.5281/zenodo.24099600) · [ResearchGate](https://www.researchgate.net/publication/354332166)

> Personal, long-term investment products, especially ones for retirement savings, require thorough understanding to use them profitably.
> Even simple savings plans based on exchange-traded funds (ETFs) are subject to many variables and uncertainties to be considered for expected and planned-upon returns.
> We present an interactive simulation of an ETF-based savings plan that combines forecasts, risk awareness, taxes and costs, inflation, and dynamic inflows and outflows into a single visualization.
> The visualization consists of four parts: a form-fill interface for configuration, a savings and payout simulation, a cash flow chart, and a savings chart.
> Based on a specific use case, we discuss how private investors can benefit from using our visualization after a short training period.

<p><a href="buessemeyer2021-etf-visualization-as-submitted.pdf"><img src="preview/page-1.webp" width="24%" alt="page 1"/></a> <a href="buessemeyer2021-etf-visualization-as-submitted.pdf"><img src="preview/page-2.webp" width="24%" alt="page 2"/></a> <a href="buessemeyer2021-etf-visualization-as-submitted.pdf"><img src="preview/page-3.webp" width="24%" alt="page 3"/></a> <a href="buessemeyer2021-etf-visualization-as-submitted.pdf"><img src="preview/page-4.webp" width="24%" alt="page 4"/></a> <a href="buessemeyer2021-etf-visualization-as-submitted.pdf"><img src="preview/page-5.webp" width="24%" alt="page 5"/></a></p>

## Contents

- [`src/`](src/) – LaTeX sources of the camera-ready version (ACM `acmart` v1.67, sigconf)
- [`buessemeyer2021-etf-visualization-as-submitted.pdf`](buessemeyer2021-etf-visualization-as-submitted.pdf) – camera-ready PDF (author build of 2021-08-18)
- [`build.sh`](build.sh) – reproducible build with TeX Live 2020 (podman or docker)
- [`preview/`](preview/) – page previews for this README

## Build

```bash
./build.sh        # → build/etf-visualization.pdf
```

The paper was compiled in August 2021 with pdfTeX 1.40.21 (TeX Live 2020), hence the TeX Live 2020 container.
The build reproduces the camera-ready PDF with identical text, pages, columns, line counts and figure placement.
Only the line breaks inside the bold figure captions on pages 1, 3 and 4 differ slightly (same words and number of lines per caption).

## Versions

- [`v1.0-camera-ready`](https://github.com/dl-archive/article.2021-vinci-etf-visualization/tree/v1.0-camera-ready) – sources as submitted to ACM (2021-08-18)

## Citation

```bibtex
@InProceedings{buessemeyer2021-etf-visualization,
  author    = {B{\"u}{\ss}emeyer, Martin and Limberger, Daniel and Scheibel, Willy and D{\"o}llner, J{\"u}rgen},
  title     = {Interactive Simulation and Visualization of Long-Term, ETF-based Investment Strategies},
  booktitle = {Proceedings of the 14th International Symposium on Visual Information Communication and Interaction},
  year      = {2021},
  series    = {VINCI~'21},
  publisher = {ACM},
  doi       = {10.1145/3481549.3481568},
  isbn      = {978-1-450386-47-0},
}
```
