![158236141-65111130-2c3a-498f-bc94-72fe2dab5352](https://user-images.githubusercontent.com/54083068/158707540-7e08b789-475d-4a3f-800a-c0197412cf53.png)


# GHES Storage Partners
GHES Storage Partners provide GitHub customers additional storage options to run GitHub Actions and GitHub Packages on GHES. These partnerships extend beyond the [current capabilities](https://docs.github.com/en/enterprise-server@3.4/admin/github-actions/enabling-github-actions-for-github-enterprise-server) at enabling GitHub Actions for GHES.

Partners that join the [GitHub Technology Partnership Program](https://partner.github.com/technology-partners) have the opportunity to self-validate their solutions.
GitHub will provide a self service test suite to validate storage product's S3-compatiable interface for each GHES version.

`Disclaimer`: GHES Storage Partners conduct all tests and self-report the data in this repository. GitHub does not independently verify the data, but expects that partners provide it in good faith. GitHub makes no express or implied representations, guarantees or warranties concerning GHES Storage Partners or their storage product(s). The data is provided as-is.


# Self-validated Solutions

| Partner<br />(A-Z) | Product<br />(one per row) | GHES 3.5 |  GHES 3.1-3.4 |  Support |  Documentation| Product Information |
|---|---|:---:|:---:|:---:|:---:|:---:|
| Hitachi Vantara  | HCP Cloud Scale v2.4.1.2 | |  **PASS**  | [Hitachi Support](https://support.hitachivantara.com/en/anonymous-dashboard.html) | [Hitachi Knowledge](https://knowledge.hitachivantara.com/Documents/Storage/HCP_for_Cloud_Scale) | [Hitachi Object Storage](https://www.hitachivantara.com/en-us/products/storage/object-storage.html) |
| MinIO | Software Defined Object Storage | **PASS** |  **PASS**  | [MinIO Subscription Network](https://min.io/product/subnet) | [MinIO Knowledge Base](https://docs.min.io/minio/k8s/) | [MinIO Object Storage](https://docs.min.io/minio/baremetal/) |
| Pure Storage | FlashBlade| |  **PASS**  | [Pure Storage Support](https://support.purestorage.com/FlashBlade) | [Pure Storage Knowledge](https://support.purestorage.com/FlashBlade/Purity_FB/FlashBlade_User_Guides) | [Pure Storage Unified Fast File Object](https://www.purestorage.com/products/file-and-object/flashblade.html) |
| Cloudian | HyperStore | **PASS** | **PASS** | [Cloudian Support](https://cloudian.com/support/) | <small>Docs are private (in product), use support if you don't have access yet</small> | [HyperStore Object Storage](https://cloudian.com/products/hyperstore/l) |
| NetApp | NetApp | **PASS** | **PASS** | TBD |TBD | TBD |

# Requirements:
- GHES Storage Partners must be members of the [GitHub Technology Partner Program](https://partner.github.com/technology-partners) to participate.
- Partners will be granted access and must [test and submit storage compatibility](https://github.com/github-technology-partners/enterprise-storage-check)(private repo) within 30 days of [new GHES version GA release.](https://docs.github.com/en/enterprise-server/admin/release-notes)
- Partners must maintain user documentation.
- Partners must commit to support joint users/customers.
