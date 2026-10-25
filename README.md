# Frohman-MixedCorrelators-FJ

<!-- ZENODO-PROVENANCE-HEADER -->
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23629490.svg)](https://doi.org/10.5281/zenodo.23629490)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--7068--3718-brightgreen.svg)](https://orcid.org/0009-0006-7068-3718)

> **Author:** Benjamin Stanley Frohman ([ORCID: 0009-0006-7068-3718](https://orcid.org/0009-0006-7068-3718))  
> **Origin Provenance:** `2026-09-25 21:43:26 CDT (Git Initial Commit)`  
> **Zenodo Archive & DOI:** [`10.5281/zenodo.23629490`](https://doi.org/10.5281/zenodo.23629490) ([Zenodo Record `23629490`](https://zenodo.org/records/23629490))  
> **Primary Manuscript PDF:** [`PROBLEM_STATEMENT.pdf`](./PROBLEM_STATEMENT.pdf)  
> **Copyright & License:** Copyright (c) 2026 Benjamin Stanley Frohman. Licensed under the Apache License, Version 2.0 ([`LICENSE`](./LICENSE), [`NOTICE`](./NOTICE)).
<!-- /ZENODO-PROVENANCE-HEADER -->


Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Textbook statement: [TEXTBOOK.md](TEXTBOOK.md)

**Problem (Frohman, mixed correlators of a three-block chain sum).**

Let $W=u^5v+v^6$ and $F=W\oplus W\oplus W$. Let $J$ scale every coordinate of $\mathbb{C}^6$ by a primitive sixth root of unity. The pair $(F,\langle J\rangle)$ is an admissible Landau–Ginzburg orbifold with $\hat{c}(F)=4$.

The FJRW state space of $(F,\langle J\rangle)$ has dimension $2610$: one broad sector of dimension $2605$ and five narrow Lefschetz states of dimension $1$.

Compute every genus-zero primary three-point number

$$
\langle\alpha,\beta,\gamma\rangle_{0,3}^{F,\langle J\rangle}
=
\int_{\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}}
\bigl[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}\bigr]^{\mathrm{vir}}
$$

where $\alpha,\beta,\gamma$ run over that $2610$-dimensional space, including mixed broad–narrow triples and mixed-block tensors, subject to the selection rule that decorations multiply to $J$.

Show that these numbers are not a product of three Guéré integrals of $W$. Produce the table, or prove vanishing, for every allowed triple.

That is the Frohman problem. It is not Guéré’s theorem.

## Status

- 216 decoration triples = 36 allowed + 180 empty-stack zeros
- Allowed mixed rooms stay OPEN
- Locked ranks: $\mu(W)=25$, $\mu(W^T)=26$, $|\det A|=30$
- Close condition: [docs/CLOSE_LINES.md](docs/CLOSE_LINES.md)
