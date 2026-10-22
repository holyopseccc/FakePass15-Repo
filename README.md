# FakePass15 Sileo repository

Public package feed for FakePass15 0.1.0 alpha 1.

Sileo source: `https://holyopseccc.github.io/FakePass15-Repo/`

Target: iPhone XR, iOS 15.6.1, Dopamine rootless. Experimental and device validation is required. This is a software lock screen, not Secure Enclave protection. No device wipe feature is included.

Package SHA-256: `4ba077fb1c7744f0b5a3f53f704468ce142cf1e1509abb5e54ebb4c3bdb7fb49`

The repository includes `libSandy 1.1.6-4+fakepass15.1`, rebuilt from the official rootless `1.1.6-4` package at <https://opa334.github.io/> so APT selects this repository's working download. Only the package version suffix and archive ownership metadata were changed; payload files and maintainer scripts were preserved. The rebuilt package SHA-256 is `96de54fb0fd3db9290c5f5703075ce190647aa3d768867e5c4599c7b28206df6`; the upstream package SHA-256 is `568c98650d8b452d68a1f893ec87f02a4f7082848b1abeec80531c4c9d484065`. libSandy is Copyright (c) 2022 Lars Fröder and distributed under the MIT License; see `LICENSE-libSandy`.
