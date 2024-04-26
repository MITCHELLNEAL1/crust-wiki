---
id: Q&AForEPID-ECDSA
title: EPID & ECDSA
sidebar_label: EPID & ECDSA
---

## 1. Overview

### EPID
Intel plans to end of life (EOL) the Intel SGX Attestation Service Utilizing Intel EPID (IAS for short) April 2, 2025. Refer to [here](https://www.intel.com/content/www/us/en/developer/articles/technical/software-security-guidance/resources/sgx-ias-using-epid-eol-timeline.html) for more information. 

### ECDSA
ECDSA-based attestation with Intel SGX DCAP allows providers to build and deliver their own attestation service instead of using the remote attestation service provided by Intel. This is a replacement for the IAS. Refer to [here](https://www.intel.com/content/www/us/en/developer/tools/software-guard-extensions/attestation-services.html) for more information. 

Crust has developed a ECDSA-based attestation service with Intel SGX DCAP. The github repo is [crust-dcap](https://github.com/crustio/crust-dcap). sWorker version >= 2.0.0 supports ECDSA-based DCAP attestation.

## 2. Migration Q&A

### 2.1 Do I need to migrate all my servers to ECDSA-based DCAP attestation before April 2, 2025?

No. sWorker 




## 3. Migration Guides