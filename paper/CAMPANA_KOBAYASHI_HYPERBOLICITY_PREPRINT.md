# Campana-Kobayashi Hyperbolicity via Orbifold-Hyperbolic Persistence
## Canonical Lane (defined term): the manifold-constrained local-to-global architecture (`CKH1-CKH8`)

**Author:** HautevilleHouse  
**Date:** March 13, 2026  
**Status:** Admissible-class theorem manuscript

---

## Abstract

This manuscript develops a canonical-lane closure architecture for the target problem: proving persistence of orbifold-hyperbolic exclusion and Kobayashi control through an admissible hyperbolic closure architecture..

The proof program is organized as eight steps `CKH1-CKH8` with executable closure gates `CKH_G1`, `CKH_G2`, `CKH_G3`, `CKH_G4`, `CKH_G5`, `CKH_G6`, and `CKH_GM`.

## 1. Target Statement and Scope

### 1.1 Target statement

The target statement is: persistence of the orbifold-hyperbolic endpoint package in the declared admissible class.

### 1.2 Local claim boundary

- the closure architecture and gate system are explicit,
- failure modes are machine-checkable,
- theorem constants are instantiated in tracked artifacts,
- repro outputs determine whether the declared admissible class closes.

## 2. Canonical Objects

Let `u_tau = (H_tau, O_tau, D_tau, N_tau, L_tau)` denote the admissible state of hyperbolic packets, orbifold data, defect ledgers, normalization parameters, and endpoint locks.

Strict closure margin:

`M_CKH = min(kappa_hyperbolic, sigma_entire, kappa_compact, rho_rigidity, orbifold_lock) - eps_coh`.

## 3. Closure Gates

- `CKH_G1`: `kappa_hyperbolic`
- `CKH_G2`: `sigma_entire`
- `CKH_G3`: `kappa_compact`
- `CKH_G4`: `rho_rigidity`
- `CKH_G5`: `orbifold_lock`
- `CKH_G6`: `eps_coh`
- `CKH_GM`: final strict margin

## 3A. Standard-Language Bridge

In ordinary complex-geometric language, the canonical-lane endpoint is the
orbifold-hyperbolic target class controlled by Kobayashi-type exclusion data on
the declared admissible family. The state `u_tau` tracks the same packet of
hyperbolic and orbifold data in the projected lane, while `orbifold_lock` and
`eps_coh` record the bridge conditions used to identify the extracted endpoint
with the standard target statement. The determining observables are recorded in
`notes/IDENTIFICATION_BRIDGE.md`.

## 4. Reproducibility

Run `bash repro/run_repro.sh` and inspect `repro/certificate_runtime.json`.
