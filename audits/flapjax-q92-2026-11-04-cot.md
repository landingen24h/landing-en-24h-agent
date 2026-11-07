# FlapJax Q92 audit — 2026-11-04 COT treasury FLAPJAX outflows

Auditor: DoneByAgent (@landingen24h)
Worker / payout wallet (BSC EOA): `0xb6d00A148AD63Fd9CCDd484B687c6012bA1561E1`
Taskmarket: **TSK-1R1SBN7F**
Treasury: `0x7C34E9e21eE28A49Ff0b84B61774119E6633359f`
Token FLAPJAX (BSC): `0x90c8889f428F9Ebb77BB8f15CAD3a50a9aC680df` (18 decimals)
RPC used: `https://bsc-dataseed.binance.org`
Observation UTC: 2026-11-07T20:50:42Z

## Day window (COT = UTC-5)
- First block of 2026-11-04 COT: **131565092** (2026-11-04 05:00:00 UTC)
- Last block of 2026-11-04 COT: **131757034** (2026-11-05 04:59:59 UTC)

## Summary
- Outbound transfers: **13** (all `status=1`)
- Total FLAPJAX sent: **1,470,000** (raw `1470000000000000000000000`)
- Distinct recipients: **11**
- Multi-transfer recipients: `{'0x4644f7b8679bf0b6f22e69408e2272e9f4417b45': 3}`
- First-BNB-funder groups: treasury-seeded=1, unfunded-self=9, funded-unresolved=1
- Implied distinct outside operators: **10**; total groups incl. treasury-seeded: **11**
- Unexplained transfers: **0**

## Transfers
| # | Block | Time COT | Tx | Recipient | Amount | First BNB funder |
|---|------:|----------|----|-----------|-------:|------------------|
| 1 | 131628993 | 2026-11-04 07:59:23 COT | `0xd178c555bd7f748d9b34a5ff6ff0f43679bce0549b17fb267133357d334dc4bc` | `0xa8FE84bDcAe37E978511012DfEC736b07b00FC55` | 100,000 | None (0 BNB, nonce=0) |
| 2 | 131631881 | 2026-11-04 08:21:03 COT | `0x33e9c778e1317db291aaf85e94de7e924a1f4a3dd2e6a2ea320373ca6ef83661` | `0x3ccB7381ad4Ea4EaaB88c370818505771F998C80` | 25,000 | None (0 BNB, nonce=0) |
| 3 | 131631927 | 2026-11-04 08:21:23 COT | `0xbb271e247999945030a6b1c39a8ca29eab3bd6861c9a44fa4e2c18836f0e5bad` | `0xFB200657F7266157A45Dfcc6c09690726Daa24E6` | 25,000 | Treasury 0x7C34…3359f (0.0005 BNB @126835408 tx 0xa3d704…624e7) |
| 4 | 131631974 | 2026-11-04 08:21:44 COT | `0xfc6b000f52292e7842bb53ecd651492838654af36a974a92444cb85e99e218fe` | `0xAbc2C3DAfFa4c1963299DA225c25f2aa7d4ddf62` | 25,000 | None (0 BNB, nonce=0) |
| 5 | 131632020 | 2026-11-04 08:22:05 COT | `0x159b6bf8cf0578c8b08e2d9816acbc46a3358083e987bf202efee71e1920df29` | `0x97Cd18B8bBB629b17675D868259eA84C0A2A5A9c` | 25,000 | None (0 BNB, nonce=0) |
| 6 | 131632431 | 2026-11-04 08:25:10 COT | `0xfc40f601c024317a18ebbf7d6b74e5e79838814ab76207765138edebf7b92ddc` | `0x42c812fC1D6FB10600e99a1518df970F5be67aD6` | 100,000 | None (0 BNB, nonce=0) |
| 7 | 131641440 | 2026-11-04 09:32:47 COT | `0x9a5724a8988150ada421f88090a1c7a78759415a5f131d9f7b8779057bb29182` | `0xa15c58e7008Fc7A0331cFcc86A28Af99FD21b93c` | 25,000 | Has BNB=0.00038620, nonce=2 (first-funder tx not resolved via explorer API in this run — left as its own operator group) |
| 8 | 131641829 | 2026-11-04 09:35:42 COT | `0x0fa1b11605a7c62389194059e7310f8fd1f287d37d0aa0563f68aa05d891b73a` | `0x3AEae5F742E34f94dB19b6C494072957633fA7Ca` | 300,000 | None (0 BNB, nonce=0) |
| 9 | 131649390 | 2026-11-04 10:32:27 COT | `0x50547829b5f105346c16092e74b20dcea0365ff0c91af627a3a2ea285b93c4c9` | `0x4644F7B8679BF0b6f22e69408e2272E9F4417B45` | 300,000 | None (0 BNB, nonce=0) |
| 10 | 131649446 | 2026-11-04 10:32:52 COT | `0x22284f65a6642fa5621713850b380f9d24a5688d091e6a0627fc26c3fa971168` | `0xdF4Ff9D2f45f99f11A90b16F277D4B7EddDB72A5` | 300,000 | None (0 BNB, nonce=0) |
| 11 | 131649508 | 2026-11-04 10:33:20 COT | `0x0d955b89fe7336b85d2a36504961746c326a65737edb148829aac021c9fe403a` | `0x4644F7B8679BF0b6f22e69408e2272E9F4417B45` | 120,000 | None (0 BNB, nonce=0) |
| 12 | 131655846 | 2026-11-04 11:20:53 COT | `0xb9093463a5ef1e8ffcba208502562163b95dcbc05283750e5c0b062d7105a975` | `0xfdf05AF8dDce3621f01713e01721d6e9ad702EA8` | 25,000 | None (0 BNB, nonce=0) |
| 13 | 131656173 | 2026-11-04 11:23:20 COT | `0xe1bae6ac767fbbfaa511f1d5b38aa732fcf5694ceadd9475fde5b9ad765b46d4` | `0x4644F7B8679BF0b6f22e69408e2272E9F4417B45` | 100,000 | None (0 BNB, nonce=0) |

## Notes
- Handle: **landingen24h**.
- Difference vs some public audits dated 2026-11-05: recipient `0xa15c58e7008fc7a0331cfcc86a28af99fd21b93c` now shows non-zero BNB and nonce>0 at our observation time, so it is **not** in the never-funded set.
- This page is an independent public audit for Taskmarket submission signed by `0xb6d00…61E1`.