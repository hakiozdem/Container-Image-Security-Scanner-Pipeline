# Before Scan
## This is vulnerability scan results before making fixes
```

Report Summary

┌──────────────────────────────────────────────────────────────────────────────────┬────────────┬─────────────────┐
│                                      Target                                      │    Type    │ Vulnerabilities │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ vuln-app:latest (debian 12.7)                                                    │   debian   │       46        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/Jinja2-3.0.3.dist-info/METADATA            │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/MarkupSafe-2.1.5.dist-info/METADATA        │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/PyYAML-5.4.1.dist-info/METADATA            │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/Werkzeug-2.0.3.dist-info/METADATA          │ python-pkg │        2        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/anyio-4.5.2.dist-info/METADATA             │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/certifi-2026.4.22.dist-info/METADATA       │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/charset_normalizer-2.0.12.dist-info/METAD- │ python-pkg │        0        │
│ ATA                                                                              │            │                 │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/click-8.1.8.dist-info/METADATA             │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/exceptiongroup-1.3.1.dist-info/METADATA    │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/fastapi-0.92.0.dist-info/METADATA          │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/h11-0.16.0.dist-info/METADATA              │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/idna-3.15.dist-info/METADATA               │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/pip-23.0.1.dist-info/METADATA              │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/pydantic-1.10.7.dist-info/METADATA         │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/requests-2.28.0.dist-info/METADATA         │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/setuptools-57.5.0.dist-info/METADATA       │ python-pkg │        3        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/sniffio-1.3.1.dist-info/METADATA           │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/starlette-0.25.0.dist-info/METADATA        │ python-pkg │        1        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/typing_extensions-4.13.2.dist-info/METADA- │ python-pkg │        0        │
│ TA                                                                               │            │                 │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/urllib3-1.26.20.dist-info/METADATA         │ python-pkg │        4        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/uvicorn-0.20.0.dist-info/METADATA          │ python-pkg │        0        │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┤
│ usr/local/lib/python3.8/site-packages/wheel-0.44.0.dist-info/METADATA            │ python-pkg │        1        │
└──────────────────────────────────────────────────────────────────────────────────┴────────────┴─────────────────┘
Legend:
- '-': Not scanned
- '0': Clean (no security findings detected)


vuln-app:latest (debian 12.7)
=============================
Total: 46 (HIGH: 39, CRITICAL: 7)

┌────────────────────┬────────────────┬──────────┬──────────────┬───────────────────┬────────────────────┬──────────────────────────────────────────────────────────────┐
│      Library       │ Vulnerability  │ Severity │    Status    │ Installed Version │   Fixed Version    │                            Title                             │
├────────────────────┼────────────────┼──────────┼──────────────┼───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ gpgv               │ CVE-2025-68973 │ HIGH     │ fixed        │ 2.2.40-1.1        │ 2.2.40-1.1+deb12u2 │ GnuPG: GnuPG: Information disclosure and potential arbitrary │
│                    │                │          │              │                   │                    │ code execution via out-of-bounds write...                    │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-68973                   │
├────────────────────┼────────────────┤          │              ├───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ libcap2            │ CVE-2026-4878  │          │              │ 1:2.66-4          │ 1:2.66-4+deb12u3   │ libcap: libcap: Privilege escalation via TOCTOU race         │
│                    │                │          │              │                   │                    │ condition in cap_set_file()                                  │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-4878                    │
├────────────────────┼────────────────┤          │              ├───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ libexpat1          │ CVE-2023-52425 │          │              │ 2.5.0-1+deb12u1   │ 2.5.0-1+deb12u2    │ expat: parsing large tokens can trigger a denial of service  │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2023-52425                   │
│                    ├────────────────┤          ├──────────────┤                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2025-59375 │          │ will_not_fix │                   │                    │ firefox: thunderbird: expat: libexpat in Expat allows        │
│                    │                │          │              │                   │                    │ attackers to trigger large dynamic...                        │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-59375                   │
│                    ├────────────────┤          ├──────────────┤                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-25210 │          │ affected     │                   │                    │ libexpat: libexpat: Information disclosure and data          │
│                    │                │          │              │                   │                    │ integrity issues due to integer overflow...                  │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-25210                   │
│                    ├────────────────┤          │              │                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-45186 │          │              │                   │                    │ libexpat: denial of service via crafted XML input            │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-45186                   │
├────────────────────┼────────────────┼──────────┼──────────────┼───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ libgnutls30        │ CVE-2026-33845 │ CRITICAL │ fixed        │ 3.7.9-2+deb12u3   │ 3.7.9-2+deb12u7    │ gnutls: GnuTLS: Denial of Service via DTLS zero-length       │
│                    │                │          │              │                   │                    │ fragment                                                     │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-33845                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-42010 │          │              │                   │                    │ gnutls: gnutls: Authentication Bypass via NUL Character in   │
│                    │                │          │              │                   │                    │ Username                                                     │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-42010                   │
│                    ├────────────────┼──────────┤              │                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2025-32988 │ HIGH     │              │                   │ 3.7.9-2+deb12u5    │ gnutls: Vulnerability in GnuTLS otherName SAN export         │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-32988                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2025-32990 │          │              │                   │                    │ gnutls: Vulnerability in GnuTLS certtool template parsing    │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-32990                   │
│                    ├────────────────┤          │              │                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-33846 │          │              │                   │ 3.7.9-2+deb12u7    │ gnutls: GnuTLS: Denial of Service via heap buffer overflow   │
│                    │                │          │              │                   │                    │ in DTLS handshake...                                         │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-33846                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-3833  │          │              │                   │                    │ gnutls: GnuTLS: Policy bypass due to case-sensitive          │
│                    │                │          │              │                   │                    │ nameConstraints comparison                                   │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-3833                    │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-42009 │          │              │                   │                    │ gnutls: gnutls: Denial of Service via DTLS packet reordering │
│                    │                │          │              │                   │                    │ vulnerability                                                │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-42009                   │
├────────────────────┼────────────────┤          ├──────────────┼───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ libgssapi-krb5-2   │ CVE-2026-40356 │          │ affected     │ 1.20.1-2+deb12u2  │                    │ krb5: MIT Kerberos 5 (krb5): Denial of Service via integer   │
│                    │                │          │              │                   │                    │ underflow and...                                             │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-40356                   │
├────────────────────┤                │          │              │                   ├────────────────────┤                                                              │
│ libk5crypto3       │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
├────────────────────┤                │          │              │                   ├────────────────────┤                                                              │
│ libkrb5-3          │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
├────────────────────┤                │          │              │                   ├────────────────────┤                                                              │
│ libkrb5support0    │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
├────────────────────┼────────────────┤          ├──────────────┼───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ liblzma5           │ CVE-2025-31115 │          │ fixed        │ 5.4.1-0.2         │ 5.4.1-1            │ xz: XZ has a heap-use-after-free bug in threaded .xz decoder │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-31115                   │
├────────────────────┼────────────────┤          ├──────────────┼───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ libncursesw6       │ CVE-2025-69720 │          │ affected     │ 6.4-4             │                    │ ncurses: ncurses: Buffer overflow vulnerability may lead to  │
│                    │                │          │              │                   │                    │ arbitrary code execution.                                    │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-69720                   │
├────────────────────┼────────────────┤          ├──────────────┼───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ libpam-modules     │ CVE-2025-6020  │          │ fixed        │ 1.5.2-6+deb12u1   │ 1.5.2-6+deb12u2    │ linux-pam: Linux-pam directory Traversal                     │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-6020                    │
├────────────────────┤                │          │              │                   │                    │                                                              │
│ libpam-modules-bin │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
├────────────────────┤                │          │              │                   │                    │                                                              │
│ libpam-runtime     │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
├────────────────────┤                │          │              │                   │                    │                                                              │
│ libpam0g           │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
├────────────────────┼────────────────┼──────────┤              ├───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ libsqlite3-0       │ CVE-2025-6965  │ CRITICAL │              │ 3.40.1-2          │ 3.40.1-2+deb12u2   │ sqlite: Integer Truncation in SQLite                         │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-6965                    │
│                    ├────────────────┤          ├──────────────┤                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2025-7458  │          │ affected     │                   │                    │ sqlite: SQLite integer overflow                              │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-7458                    │
│                    ├────────────────┼──────────┼──────────────┤                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2023-7104  │ HIGH     │ fixed        │                   │ 3.40.1-2+deb12u1   │ sqlite: heap-buffer-overflow at sessionfuzz                  │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2023-7104                    │
├────────────────────┼────────────────┼──────────┤              ├───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ libssl3            │ CVE-2026-31789 │ CRITICAL │              │ 3.0.14-1~deb12u2  │ 3.0.19-1~deb12u2   │ openssl: OpenSSL: Heap buffer overflow on 32-bit systems     │
│                    │                │          │              │                   │                    │ from large X.509 certificate...                              │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-31789                   │
│                    ├────────────────┼──────────┤              │                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2025-15467 │ HIGH     │              │                   │ 3.0.18-1~deb12u2   │ openssl: OpenSSL: Remote code execution or Denial of Service │
│                    │                │          │              │                   │                    │ via oversized Initialization...                              │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-15467                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2025-69421 │          │              │                   │                    │ openssl: OpenSSL: Denial of Service via malformed PKCS#12    │
│                    │                │          │              │                   │                    │ file processing                                              │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-69421                   │
│                    ├────────────────┤          │              │                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-28387 │          │              │                   │ 3.0.19-1~deb12u2   │ openssl: OpenSSL: Arbitrary code execution due to            │
│                    │                │          │              │                   │                    │ use-after-free in DANE TLSA authentication...                │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-28387                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-28388 │          │              │                   │                    │ openssl: OpenSSL: Denial of Service due to NULL pointer      │
│                    │                │          │              │                   │                    │ dereference in delta...                                      │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-28388                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-28389 │          │              │                   │                    │ openssl: OpenSSL: Denial of Service vulnerability in CMS     │
│                    │                │          │              │                   │                    │ processing                                                   │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-28389                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-28390 │          │              │                   │                    │ openssl: OpenSSL: Denial of Service due to NULL pointer      │
│                    │                │          │              │                   │                    │ dereference in CMS...                                        │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-28390                   │
├────────────────────┼────────────────┤          ├──────────────┼───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ libtinfo6          │ CVE-2025-69720 │          │ affected     │ 6.4-4             │                    │ ncurses: ncurses: Buffer overflow vulnerability may lead to  │
│                    │                │          │              │                   │                    │ arbitrary code execution.                                    │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-69720                   │
├────────────────────┤                │          │              │                   ├────────────────────┤                                                              │
│ ncurses-base       │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
├────────────────────┤                │          │              │                   ├────────────────────┤                                                              │
│ ncurses-bin        │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
│                    │                │          │              │                   │                    │                                                              │
├────────────────────┼────────────────┼──────────┼──────────────┼───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ openssl            │ CVE-2026-31789 │ CRITICAL │ fixed        │ 3.0.14-1~deb12u2  │ 3.0.19-1~deb12u2   │ openssl: OpenSSL: Heap buffer overflow on 32-bit systems     │
│                    │                │          │              │                   │                    │ from large X.509 certificate...                              │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-31789                   │
│                    ├────────────────┼──────────┤              │                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2025-15467 │ HIGH     │              │                   │ 3.0.18-1~deb12u2   │ openssl: OpenSSL: Remote code execution or Denial of Service │
│                    │                │          │              │                   │                    │ via oversized Initialization...                              │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-15467                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2025-69421 │          │              │                   │                    │ openssl: OpenSSL: Denial of Service via malformed PKCS#12    │
│                    │                │          │              │                   │                    │ file processing                                              │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2025-69421                   │
│                    ├────────────────┤          │              │                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-28387 │          │              │                   │ 3.0.19-1~deb12u2   │ openssl: OpenSSL: Arbitrary code execution due to            │
│                    │                │          │              │                   │                    │ use-after-free in DANE TLSA authentication...                │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-28387                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-28388 │          │              │                   │                    │ openssl: OpenSSL: Denial of Service due to NULL pointer      │
│                    │                │          │              │                   │                    │ dereference in delta...                                      │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-28388                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-28389 │          │              │                   │                    │ openssl: OpenSSL: Denial of Service vulnerability in CMS     │
│                    │                │          │              │                   │                    │ processing                                                   │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-28389                   │
│                    ├────────────────┤          │              │                   │                    ├──────────────────────────────────────────────────────────────┤
│                    │ CVE-2026-28390 │          │              │                   │                    │ openssl: OpenSSL: Denial of Service due to NULL pointer      │
│                    │                │          │              │                   │                    │ dereference in CMS...                                        │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2026-28390                   │
├────────────────────┼────────────────┤          │              ├───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ perl-base          │ CVE-2023-31484 │          │              │ 5.36.0-7+deb12u1  │ 5.36.0-7+deb12u3   │ perl: CPAN.pm does not verify TLS certificates when          │
│                    │                │          │              │                   │                    │ downloading distributions over HTTPS...                      │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2023-31484                   │
│                    ├────────────────┤          │              │                   ├────────────────────┼──────────────────────────────────────────────────────────────┤
│                    │ CVE-2024-56406 │          │              │                   │ 5.36.0-7+deb12u2   │ perl: Perl 5.34, 5.36, 5.38 and 5.40 are vulnerable to a     │
│                    │                │          │              │                   │                    │ heap...                                                      │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2024-56406                   │
├────────────────────┼────────────────┼──────────┼──────────────┼───────────────────┼────────────────────┼──────────────────────────────────────────────────────────────┤
│ zlib1g             │ CVE-2023-45853 │ CRITICAL │ will_not_fix │ 1:1.2.13.dfsg-1   │                    │ zlib: integer overflow and resultant heap-based buffer       │
│                    │                │          │              │                   │                    │ overflow in zipOpenNewFileInZip4_6                           │
│                    │                │          │              │                   │                    │ https://avd.aquasec.com/nvd/cve-2023-45853                   │
└────────────────────┴────────────────┴──────────┴──────────────┴───────────────────┴────────────────────┴──────────────────────────────────────────────────────────────┘

Python (python-pkg)
===================
Total: 11 (HIGH: 11, CRITICAL: 0)

┌───────────────────────┬────────────────┬──────────┬────────┬───────────────────┬───────────────┬─────────────────────────────────────────────────────────────┐
│        Library        │ Vulnerability  │ Severity │ Status │ Installed Version │ Fixed Version │                            Title                            │
├───────────────────────┼────────────────┼──────────┼────────┼───────────────────┼───────────────┼─────────────────────────────────────────────────────────────┤
│ Werkzeug (METADATA)   │ CVE-2023-25577 │ HIGH     │ fixed  │ 2.0.3             │ 2.2.3         │ python-werkzeug: high resource usage when parsing multipart │
│                       │                │          │        │                   │               │ form data with many fields...                               │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2023-25577                  │
│                       ├────────────────┤          │        │                   ├───────────────┼─────────────────────────────────────────────────────────────┤
│                       │ CVE-2024-34069 │          │        │                   │ 3.0.3         │ python-werkzeug: user may execute code on a developer's     │
│                       │                │          │        │                   │               │ machine                                                     │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2024-34069                  │
├───────────────────────┼────────────────┤          │        ├───────────────────┼───────────────┼─────────────────────────────────────────────────────────────┤
│ setuptools (METADATA) │ CVE-2022-40897 │          │        │ 57.5.0            │ 65.5.1        │ pypa-setuptools: Regular Expression Denial of Service       │
│                       │                │          │        │                   │               │ (ReDoS) in package_index.py                                 │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2022-40897                  │
│                       ├────────────────┤          │        │                   ├───────────────┼─────────────────────────────────────────────────────────────┤
│                       │ CVE-2024-6345  │          │        │                   │ 70.0.0        │ pypa/setuptools: Remote code execution via download         │
│                       │                │          │        │                   │               │ functions in the package_index module in...                 │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2024-6345                   │
│                       ├────────────────┤          │        │                   ├───────────────┼─────────────────────────────────────────────────────────────┤
│                       │ CVE-2025-47273 │          │        │                   │ 78.1.1        │ setuptools: Path Traversal Vulnerability in setuptools      │
│                       │                │          │        │                   │               │ PackageIndex                                                │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2025-47273                  │
├───────────────────────┼────────────────┤          │        ├───────────────────┼───────────────┼─────────────────────────────────────────────────────────────┤
│ starlette (METADATA)  │ CVE-2024-47874 │          │        │ 0.25.0            │ 0.40.0        │ starlette: Starlette Denial of service (DoS) via            │
│                       │                │          │        │                   │               │ multipart/form-data                                         │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2024-47874                  │
├───────────────────────┼────────────────┤          │        ├───────────────────┼───────────────┼─────────────────────────────────────────────────────────────┤
│ urllib3 (METADATA)    │ CVE-2025-66418 │          │        │ 1.26.20           │ 2.6.0         │ urllib3: urllib3: Unbounded decompression chain leads to    │
│                       │                │          │        │                   │               │ resource exhaustion                                         │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2025-66418                  │
│                       ├────────────────┤          │        │                   │               ├─────────────────────────────────────────────────────────────┤
│                       │ CVE-2025-66471 │          │        │                   │               │ urllib3: urllib3 Streaming API improperly handles highly    │
│                       │                │          │        │                   │               │ compressed data                                             │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2025-66471                  │
│                       ├────────────────┤          │        │                   ├───────────────┼─────────────────────────────────────────────────────────────┤
│                       │ CVE-2026-21441 │          │        │                   │ 2.6.3         │ urllib3: urllib3 vulnerable to decompression-bomb safeguard │
│                       │                │          │        │                   │               │ bypass when following HTTP redirects (streaming...          │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2026-21441                  │
│                       ├────────────────┤          │        │                   ├───────────────┼─────────────────────────────────────────────────────────────┤
│                       │ CVE-2026-44431 │          │        │                   │ 2.7.0         │ urllib3 is an HTTP client library for Python. From 1.23 to  │
│                       │                │          │        │                   │               │ before...                                                   │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2026-44431                  │
├───────────────────────┼────────────────┤          │        ├───────────────────┼───────────────┼─────────────────────────────────────────────────────────────┤
│ wheel (METADATA)      │ CVE-2026-24049 │          │        │ 0.44.0            │ 0.46.2        │ wheel: wheel: Privilege Escalation or Arbitrary Code        │
│                       │                │          │        │                   │               │ Execution via malicious wheel file...                       │
│                       │                │          │        │                   │               │ https://avd.aquasec.com/nvd/cve-2026-24049                  │
└───────────────────────┴────────────────┴──────────┴────────┴───────────────────┴───────────────┴─────────────────────────────────────────────────────────────┘
```