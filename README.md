# Neural EBSD Explorer

Live demo: https://neural-ebsd.github.io/

## Summary

An interactive, fully-static explorer for a **Tensor-Factorized Implicit Neural
Representation (TF-INR)** of EBSD Kikuchi patterns. It lets a reader compare measured
patterns against neural reconstructions with honest error metrics, drag a probe
*continuously* across the specimen at off-grid positions, and interrogate the
analytic **diffraction gradient field** `S(x,y)` computed from the SIREN Jacobian.

## License

Three-way split — the code, our data, and someone else's data are not the same thing:

- **Present application** (frontend in `app/`): see [`LICENSE`](LICENSE).

- **Ground-truth Kikuchi patterns** (`app/data/rx/tiles/`): experimental data from Calvat et al. published on Dryad ([`10.5061/dryad.zcrjdfnr9`](https://doi.org/10.5061/dryad.zcrjdfnr9)), **CC0 1.0 Universal**, redistributed in derived (WebP tile) form with attribution. See [`THIRD-PARTY.md`](THIRD-PARTY.md).

**Patent pending** — the license here grants no patent rights; see [`PATENTS.md`](PATENTS.md).

© 2026 Arizona Board of Regents on behalf of the University of Arizona.

## Citation

Please cite this work as

```
@article{huang2026neural,
  title={Neural electron backscatter diffraction},
  author={Huang, I-Tzu and Latypov, Marat I},
  journal={arXiv preprint arXiv:2606.10352},
  year={2026}
}
```