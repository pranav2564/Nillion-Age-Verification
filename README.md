# Age Verification with Nillion

A privacy-preserving age verification system using Nillion's secure computation technology.

## Overview

This application demonstrates how individuals can prove they are of legal age without revealing their exact age, enhancing privacy while maintaining trust in the verification process.

## How This App Works

1. **Secret Age Inputs:** Individual and trusted authority provide secret age inputs.
2. **Secure Computation:** Nillion performs computation, yielding a random integer.
3. **Verification Logic:** Positive result if both inputs indicate 18+, negative otherwise.
4. **Result Display:** Frontend interprets the result (positive = legal age, negative = under 18 or discrepancy).

## Key Features

- Privacy-preserving: Exact ages never revealed
- Double verification: Requires agreement between individual and authority
- Zero-knowledge proof: Proves age eligibility without disclosing specific information

## Installation & Setup

### Prerequisites

- Node.js and Yarn
- Familiarity with blockchain and web3 technologies

### Steps

1. **Nillion Setup:**
   Follow [Nillion's quickstart guide](https://docs.nillion.com/js-quickstart)

2. **Project Setup:**
   ```bash
   git clone [https://github.com/pranav2564/Nillion-Age-Verification.git]
   cd scaffold-nillion-age-verification
   yarn install

3. **Run Nillion Devnet**
    ```bash
    yarn nillion-devnet

4.  **Run Local Chain**
    ```bash
    yarn chain

5.  **Launch The App**
    ```bash
    yarn start