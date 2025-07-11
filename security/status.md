<!-- DO NOT EDIT. This document is automatically generated by running `make vex-report`. -->
# Vulnerability Report

Following is the vulnerability report of Fleet and its dependencies.

## `fleetdm/fleet` docker image

### [CVE-2025-46569](https://nvd.nist.gov/vuln/detail/CVE-2025-46569)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleet does not use OPA in server mode, it uses it as a library.
- **Products:**: `fleet`,`pkg:golang/github.com/open-policy-agent/opa@v0.44.0`,`pkg:golang/github.com/open-policy-agent/opa@0.44.0`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-05-05 20:29:07

### [CVE-2025-30204](https://nvd.nist.gov/vuln/detail/CVE-2025-30204)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** The token format being validated before the call to ParseUnverified.
- **Products:**: `fleet`,`pkg:golang/github.com/golang-jwt/jwt/v4`
- **Justification:** `inline_mitigations_already_exist`
- **Timestamp:** 2025-04-10 15:23:54

### [CVE-2025-27509](https://nvd.nist.gov/vuln/detail/CVE-2025-27509)
#### Statement:
- **Author:** @lucasmrod
- **Status:** `fixed`
- **Products:**: `cpe:2.3:a:fleetdm:fleet:v4.64.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.63.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.62.4:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.58.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.53.2:*:*:*:*:*:*:*`
- **Timestamp:** 2025-05-12 16:30:30

#### Statement:
- **Author:** @lucasmrod
- **Status:** `affected`
- **Products:**: `cpe:2.3:a:fleetdm:fleet:v4.64.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.64.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.63.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.63.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.62.3:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.62.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.62.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.62.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.61.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.60.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.60.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.59.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.59.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.58.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.57.3:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.57.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.57.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.57.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.56.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.55.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.55.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.55.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.54.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.54.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.54.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.53.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.53.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.52.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.51.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.51.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.50.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.50.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.50.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.49.4:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.49.3:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.49.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.49.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.49.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.48.3:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.48.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.48.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.48.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.47.3:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.47.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.47.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.47.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.46.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.46.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.46.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.45.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.45.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.44.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.44.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.43.3:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.43.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.43.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.43.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.42.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.41.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.41.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.40.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.39.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.38.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.38.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.37.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.36.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.35.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.35.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.35.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.34.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.34.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.33.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.33.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.32.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.31.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.31.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.30.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.30.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.29.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.29.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.28.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.28.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.27.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.27.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.26.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.25.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.24.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.24.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.23.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.22.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.22.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.21.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.20.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.20.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.19.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.19.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.18.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.17.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.17.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.16.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.15.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.14.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.13.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.13.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.13.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.12.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.12.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.11.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.10.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.9.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.9.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.8.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.7.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.6.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.6.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.6.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.5.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.5.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.4.3:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.4.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.4.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.4.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.3.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.3.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.3.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.2.4:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.2.3:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.2.2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.2.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.2.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.1.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.0.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.0.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.0.0-rc3:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.0.0-rc2:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v4.0.0-rc1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.13.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.12.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.11.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.10.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.10.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.9.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.8.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.7.4:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.7.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.7.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.6.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.5.1:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.5.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.4.0:*:*:*:*:*:*:*`,`cpe:2.3:a:fleetdm:fleet:v3.3.0:*:*:*:*:*:*:*`
- **Action statement:** `Disable SAML SSO authentication.`
- **Timestamp:** 2025-05-12 16:13:23

### [CVE-2025-26519](https://nvd.nist.gov/vuln/detail/CVE-2025-26519)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleet does not perform any EUC-KR to UTF-8 translation by libc.
- **Products:**: `fleet`,`pkg:apk/alpine/musl@1.2.5-r8?os_name=alpine&os_version=3.21`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-14 16:30:01

### [CVE-2025-22874](https://nvd.nist.gov/vuln/detail/CVE-2025-22874)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** Fleet does not perform any verification of policies in client certificates (CertificatePolicies not set in VerifyOptions).
- **Products:**: `fleet`,`pkg:golang/stdlib@1.24.2`
- **Justification:** `vulnerable_code_cannot_be_controlled_by_adversary`
- **Timestamp:** 2025-06-23 16:48:42

### [CVE-2025-21614](https://nvd.nist.gov/vuln/detail/CVE-2025-21614)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** The fleetctl executable is unused in the fleetdm/fleet docker image. The executable was removed in v4.64.0.
- **Products:**: `fleet`,`pkg:golang/github.com/go-git/go-git/v5`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-10 15:43:15

### [CVE-2025-21613](https://nvd.nist.gov/vuln/detail/CVE-2025-21613)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** The fleetctl executable is unused in the fleetdm/fleet docker image. The executable was removed in v4.64.0.
- **Products:**: `fleet`,`pkg:golang/github.com/go-git/go-git/v5`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-10 15:42:55

### [CVE-2024-8260](https://nvd.nist.gov/vuln/detail/CVE-2024-8260)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** Fleet doesn't run on Windows, so it's not affected by this vulnerability.
- **Products:**: `fleet`,`pkg:golang/github.com/open-policy-agent/opa`
- **Justification:** `vulnerable_code_cannot_be_controlled_by_adversary`
- **Timestamp:** 2025-05-05 20:54:14

### [CVE-2024-12797](https://nvd.nist.gov/vuln/detail/CVE-2024-12797)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleet uses Go TLS implementation.
- **Products:**: `fleet`,`pkg:apk/alpine/libcrypto3`,`pkg:apk/alpine/libssl3`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-10 15:15:53

### [CVE-2023-32698](https://nvd.nist.gov/vuln/detail/CVE-2023-32698)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** The fleetctl executable is unused in the fleetdm/fleet docker image. The executable was removed in v4.64.0.
- **Products:**: `fleet`,`pkg:golang/github.com/goreleaser/nfpm/v2`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-10 15:28:30

## `fleetdm/fleetctl` docker image

### [CVE-2025-49796](https://nvd.nist.gov/vuln/detail/CVE-2025-49796)
- **Author:** @sgress454
- **Status:** `not_affected`
- **Status notes:** The affected dependency (libxml2) is not utilized by fleetctl itself, but by Apple’s iTMSTransporter tool, which is included in the Docker image for code signing purposes. fleetctl does not process untrusted XML input. Additionally, this CVE describes a denial-of-service (DoS) vulnerability, and fleetctl is a CLI tool, not a long-running service, and therefore is not susceptible to DoS-style exploitation.
- **Products:**: `fleetctl`,`pkg:deb/debian/libxml2@2.9.14+dfsg-1.3~deb12u1`
- **Justification:** `vulnerable_code_cannot_be_controlled_by_adversary`
- **Timestamp:** 2025-06-13 15:57:38

### [CVE-2025-49795](https://nvd.nist.gov/vuln/detail/CVE-2025-49795)
- **Author:** @sgress454
- **Status:** `not_affected`
- **Status notes:** The affected dependency (libxml2) is not utilized by fleetctl itself, but by Apple’s iTMSTransporter tool, which is included in the Docker image for code signing purposes. fleetctl does not process untrusted XML input. Additionally, this CVE describes a denial-of-service (DoS) vulnerability, and fleetctl is a CLI tool, not a long-running service, and therefore is not susceptible to DoS-style exploitation.
- **Products:**: `fleetctl`,`pkg:deb/debian/libxml2@2.9.14+dfsg-1.3~deb12u1`
- **Justification:** `vulnerable_code_cannot_be_controlled_by_adversary`
- **Timestamp:** 2025-06-13 15:57:25

### [CVE-2025-49794](https://nvd.nist.gov/vuln/detail/CVE-2025-49794)
- **Author:** @sgress454
- **Status:** `not_affected`
- **Status notes:** The affected dependency (libxml2) is not utilized by fleetctl itself, but by Apple’s iTMSTransporter tool, which is included in the Docker image for code signing purposes. fleetctl does not process untrusted XML input. Additionally, this CVE describes a denial-of-service (DoS) vulnerability, and fleetctl is a CLI tool, not a long-running service, and therefore is not susceptible to DoS-style exploitation.
- **Products:**: `fleetctl`,`pkg:deb/debian/libxml2@2.9.14+dfsg-1.3~deb12u1`
- **Justification:** `vulnerable_code_cannot_be_controlled_by_adversary`
- **Timestamp:** 2025-06-13 15:56:50

### [CVE-2025-48734](https://nvd.nist.gov/vuln/detail/CVE-2025-48734)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** The fleetctl tool is used by IT admins to generate packages so the vulnerable code cannot be controlled by attackers.
- **Products:**: `fleetctl`,`pkg:maven/commons-beanutils/commons-beanutils`
- **Justification:** `vulnerable_code_cannot_be_controlled_by_adversary`
- **Timestamp:** 2025-06-02 07:33:44

### [CVE-2025-46569](https://nvd.nist.gov/vuln/detail/CVE-2025-46569)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleetctl does not use OPA.
- **Products:**: `fleetctl`,`pkg:golang/github.com/open-policy-agent/opa`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-05-06 07:47:31

### [CVE-2025-31115](https://nvd.nist.gov/vuln/detail/CVE-2025-31115)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleetctl does not use liblzma5.
- **Products:**: `fleetctl`,`pkg:deb/debian/liblzma5`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-09 13:24:20

### [CVE-2024-7254](https://nvd.nist.gov/vuln/detail/CVE-2024-7254)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleetctl does not use Java.
- **Products:**: `fleetctl`,`pkg:maven/com.google.protobuf/protobuf-java`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-10 07:34:26

### [CVE-2023-6879](https://nvd.nist.gov/vuln/detail/CVE-2023-6879)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleetctl does not use libaom3.
- **Products:**: `fleetctl`,`pkg:deb/debian/libaom3`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-15 10:28:21

### [CVE-2023-45853](https://nvd.nist.gov/vuln/detail/CVE-2023-45853)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleetctl does not use zlib C library.
- **Products:**: `fleetctl`,`pkg:deb/debian/zlib1g`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-15 10:17:19

### [CVE-2023-32698](https://nvd.nist.gov/vuln/detail/CVE-2023-32698)
- **Author:** @getvictor
- **Status:** `not_affected`
- **Status notes:** When packaging linux files, fleetctl does not use global permissions. It was verified that packed fleetd package files do not have group/global write permissions.
- **Products:**: `fleetctl`,`pkg:golang/github.com/goreleaser/nfpm/v2`
- **Justification:** `vulnerable_code_cannot_be_controlled_by_adversary`
- **Timestamp:** 2025-04-09 10:26:02

### [CVE-2019-10202](https://nvd.nist.gov/vuln/detail/CVE-2019-10202)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleetctl does not use Java.
- **Products:**: `fleetctl`,`pkg:maven/org.codehaus.jackson/jackson-mapper-asl`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-15 10:31:31

### [CVE-2013-4002](https://nvd.nist.gov/vuln/detail/CVE-2013-4002)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleetctl does not use Java.
- **Products:**: `fleetctl`,`pkg:maven/xerces/xercesImpl`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-10 07:36:31

### [CVE-2012-0881](https://nvd.nist.gov/vuln/detail/CVE-2012-0881)
- **Author:** @lucasmrod
- **Status:** `not_affected`
- **Status notes:** fleetctl does not use Java.
- **Products:**: `fleetctl`,`pkg:maven/xerces/xercesImpl`
- **Justification:** `vulnerable_code_not_in_execute_path`
- **Timestamp:** 2025-04-10 14:46:52

