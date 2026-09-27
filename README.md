# SYSU-MM01

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FSYSU--MM01-181717?logo=github)](https://github.com/biometric-community/SYSU-MM01)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://github.com/wuancong/SYSU-MM01)

**SYSU-MM01** — tbiom catalog packaging for `sysu-mm01` (reid; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/SYSU-MM01
- **Upstream source**: https://github.com/wuancong/SYSU-MM01
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `sysu-mm01` |
| Category | `reid` |
| Access | `register` |
| Upstream homepage | https://github.com/wuancong/SYSU-MM01 |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: RGB-IR re-ID; request via project page.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/SYSU-MM01.git
cd SYSU-MM01
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_sysu_mm01.sh
```

Place licensed archives under `projects/datasets/sysu-mm01/` (gitignored).

## Dataset structure

```text
SYSU-MM01/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://github.com/wuancong/SYSU-MM01
- Packaging: https://github.com/biometric-community/SYSU-MM01/issues
