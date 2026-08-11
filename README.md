<p align="center">
  <h1 align="center">Role Inference From Style Versus Delimiters</h1>
  <p align="center"><strong>Measure whether models trust writing style over structural role tags under injection.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Role Inference From Style Versus Delimiters**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Measure whether models trust writing style over structural role tags under injection.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
