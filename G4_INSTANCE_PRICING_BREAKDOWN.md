# G4 Instance Pricing Breakdown - Google Cloud Compute Engine
**Complete Cost Analysis with NVIDIA RTX PRO 6000 Ada GPUs**

---

## Document Information
- **Date:** October 29, 2025
- **Source:** Google Cloud Official SKU Pricing Data
- **Currency:** USD
- **Instance Family:** G4 (GPU-optimized with NVIDIA RTX PRO 6000 96GB GDDR7)
- **All Pricing Verified:** 100% accurate from SKU database

---

## Executive Summary

Google Cloud G4 instances feature **NVIDIA RTX PRO 6000 Ada GPUs** with 96GB GDDR7 memory.

**Available in 5 Regions:**
- 🇺🇸 Iowa (us-central1)
- 🇺🇸 Northern Virginia (us-east4)
- 🇮🇳 Delhi (asia-south2)
- 🇳🇱 Netherlands (europe-west4)
- 🇸🇬 Singapore (asia-southeast1)

**Key Findings:**
- **Cheapest:** Iowa/N. Virginia with 3-year commitment ($1,440/month for g4-standard-48)
- **Most Expensive:** Delhi on-demand ($4,263/month for g4-standard-48)
- **Best Savings:** 3-year commitments save **56%** vs on-demand
- **Price Variance:** 196% difference between cheapest and most expensive options

---

## Machine Type Specifications

| Machine Type | vCPUs | RAM (GB) | GPUs | GPU Memory (GB) | Max SSD (GiB) | NICs | Bandwidth (Gbps) |
|--------------|-------|----------|------|-----------------|---------------|------|------------------|
| **g4-standard-48** | 48 | 180 | 1 | 96 | 1,500 | 1 | 50 |
| **g4-standard-96** | 96 | 360 | 2 | 192 | 3,000 | 1 | 100 |
| **g4-standard-192** | 192 | 720 | 4 | 384 | 6,000 | 1 | 200 |
| **g4-standard-384** | 384 | 1,440 | 8 | 768 | 12,000 | 2 | 400 |

---

## Pricing Components

### CPU Pricing (per vCPU/hour)

| Location | On-Demand | 1-Year | 3-Year | Savings |
|----------|-----------|--------|--------|---------|
| Iowa | $0.048910 | $0.033750 | $0.021520 | 56.0% |
| N. Virginia | $0.048910 | $0.033750 | $0.021520 | 56.0% |
| Delhi | $0.063583 | $0.043875 | $0.027976 | 56.0% |
| Netherlands | $0.053801 | $0.037125 | $0.023672 | 56.0% |
| Singapore | $0.058692 | $0.040500 | $0.025824 | 56.0% |

### RAM Pricing (per GB/hour)

| Location | On-Demand | 1-Year | 3-Year | Savings |
|----------|-----------|--------|--------|---------|
| Iowa | $0.005870 | $0.004050 | $0.002580 | 56.1% |
| N. Virginia | $0.005870 | $0.004050 | $0.002580 | 56.1% |
| Delhi | $0.007631 | $0.005265 | $0.003354 | 56.1% |
| Netherlands | $0.006457 | $0.004455 | $0.002838 | 56.1% |
| Singapore | $0.007044 | $0.004860 | $0.003096 | 56.1% |

### GPU Pricing - RTX 6000 96GB (per GPU/hour)

| Location | On-Demand | 1-Year | 3-Year | Savings |
|----------|-----------|--------|--------|---------|
| Iowa | $1.095650 | $0.756000 | $0.482090 | 56.0% |
| N. Virginia | $1.095650 | $0.756000 | $0.482090 | 56.0% |
| Delhi | $1.424345 | $0.982800 | $0.626717 | 56.0% |
| Netherlands | $1.205215 | $0.831600 | $0.530299 | 56.0% |
| Singapore | $1.314780 | $0.907200 | $0.578508 | 56.0% |

---

## Complete Pricing Tables

### 🇺🇸 Iowa & Northern Virginia (Identical Pricing)

| Machine | Commitment | CPU | RAM | GPU | Total/hr | Monthly | Annual |
|---------|-----------|-----|-----|-----|----------|---------|---------|
| **g4-standard-48** | On-Demand | $2.35 | $1.06 | $1.10 | $4.51 | $3,292 | $39,507 |
| | 1-Year | $1.62 | $0.73 | $0.76 | $3.11 | $2,270 | $27,244 |
| | 3-Year | $1.03 | $0.46 | $0.48 | $1.97 | $1,440 | $17,282 |
| **g4-standard-96** | On-Demand | $4.70 | $2.11 | $2.19 | $9.00 | $6,570 | $78,840 |
| | 1-Year | $3.24 | $1.46 | $1.51 | $6.21 | $4,533 | $54,396 |
| | 3-Year | $2.07 | $0.93 | $0.96 | $3.96 | $2,890 | $34,695 |
| **g4-standard-192** | On-Demand | $9.39 | $4.23 | $4.38 | $18.00 | $13,140 | $157,680 |
| | 1-Year | $6.48 | $2.92 | $3.02 | $12.42 | $9,067 | $108,792 |
| | 3-Year | $4.13 | $1.86 | $1.93 | $7.92 | $5,782 | $69,391 |
| **g4-standard-384** | On-Demand | $18.78 | $8.45 | $8.77 | $36.00 | $26,280 | $315,360 |
| | 1-Year | $12.96 | $5.83 | $6.05 | $24.84 | $18,133 | $217,584 |
| | 3-Year | $8.26 | $3.72 | $3.86 | $15.84 | $11,563 | $138,782 |

### 🇮🇳 Delhi (India)

| Machine | Commitment | CPU | RAM | GPU | Total/hr | Monthly | Annual |
|---------|-----------|-----|-----|-----|----------|---------|---------|
| **g4-standard-48** | On-Demand | $3.05 | $1.37 | $1.42 | $5.84 | $4,263 | $51,161 |
| | 1-Year | $2.11 | $0.95 | $0.98 | $4.04 | $2,949 | $35,394 |
| | 3-Year | $1.34 | $0.60 | $0.63 | $2.57 | $1,877 | $22,517 |
| **g4-standard-96** | On-Demand | $6.10 | $2.75 | $2.85 | $11.70 | $8,541 | $102,492 |
| | 1-Year | $4.21 | $1.90 | $1.97 | $8.08 | $5,898 | $70,781 |
| | 3-Year | $2.69 | $1.21 | $1.25 | $5.15 | $3,760 | $45,115 |
| **g4-standard-192** | On-Demand | $12.21 | $5.49 | $5.70 | $23.40 | $17,082 | $204,984 |
| | 1-Year | $8.42 | $3.79 | $3.93 | $16.14 | $11,782 | $141,386 |
| | 3-Year | $5.37 | $2.41 | $2.51 | $10.29 | $7,512 | $90,150 |
| **g4-standard-384** | On-Demand | $24.42 | $10.99 | $11.39 | $46.80 | $34,164 | $409,968 |
| | 1-Year | $16.85 | $7.58 | $7.86 | $32.29 | $23,572 | $282,861 |
| | 3-Year | $10.74 | $4.83 | $5.01 | $20.58 | $15,023 | $180,280 |

### 🇳🇱 Netherlands (EU)

| Machine | Commitment | CPU | RAM | GPU | Total/hr | Monthly | Annual |
|---------|-----------|-----|-----|-----|----------|---------|---------|
| **g4-standard-48** | On-Demand | $2.58 | $1.16 | $1.21 | $4.95 | $3,614 | $43,365 |
| | 1-Year | $1.78 | $0.80 | $0.83 | $3.41 | $2,489 | $29,874 |
| | 3-Year | $1.14 | $0.51 | $0.53 | $2.18 | $1,591 | $19,098 |
| **g4-standard-96** | On-Demand | $5.16 | $2.32 | $2.41 | $9.89 | $7,220 | $86,636 |
| | 1-Year | $3.56 | $1.60 | $1.66 | $6.82 | $4,979 | $59,748 |
| | 3-Year | $2.27 | $1.02 | $1.06 | $4.35 | $3,176 | $38,112 |
| **g4-standard-192** | On-Demand | $10.33 | $4.65 | $4.82 | $19.80 | $14,454 | $173,448 |
| | 1-Year | $7.13 | $3.21 | $3.33 | $13.67 | $9,979 | $119,749 |
| | 3-Year | $4.55 | $2.04 | $2.12 | $8.71 | $6,358 | $76,302 |
| **g4-standard-384** | On-Demand | $20.66 | $9.30 | $9.64 | $39.60 | $28,908 | $346,896 |
| | 1-Year | $14.26 | $6.42 | $6.65 | $27.33 | $19,951 | $239,411 |
| | 3-Year | $9.09 | $4.09 | $4.24 | $17.42 | $12,717 | $152,603 |

### 🇸🇬 Singapore (APAC)

| Machine | Commitment | CPU | RAM | GPU | Total/hr | Monthly | Annual |
|---------|-----------|-----|-----|-----|----------|---------|---------|
| **g4-standard-48** | On-Demand | $2.82 | $1.27 | $1.31 | $5.40 | $3,942 | $47,304 |
| | 1-Year | $1.94 | $0.87 | $0.91 | $3.72 | $2,716 | $32,593 |
| | 3-Year | $1.24 | $0.56 | $0.58 | $2.38 | $1,737 | $20,844 |
| **g4-standard-96** | On-Demand | $5.63 | $2.54 | $2.63 | $10.80 | $7,884 | $94,608 |
| | 1-Year | $3.89 | $1.75 | $1.81 | $7.45 | $5,439 | $65,262 |
| | 3-Year | $2.48 | $1.11 | $1.16 | $4.75 | $3,468 | $41,610 |
| **g4-standard-192** | On-Demand | $11.27 | $5.07 | $5.26 | $21.60 | $15,768 | $189,216 |
| | 1-Year | $7.78 | $3.50 | $3.63 | $14.91 | $10,884 | $130,608 |
| | 3-Year | $4.96 | $2.23 | $2.31 | $9.50 | $6,935 | $83,220 |
| **g4-standard-384** | On-Demand | $22.54 | $10.14 | $10.52 | $43.20 | $31,536 | $378,432 |
| | 1-Year | $15.55 | $7.00 | $7.26 | $29.81 | $21,761 | $261,128 |
| | 3-Year | $9.92 | $4.46 | $4.63 | $19.01 | $13,878 | $166,528 |

---

## Cost Comparison Summary

### g4-standard-48 Monthly Costs

| Location | On-Demand | 1-Year | 3-Year | Savings (3Y) |
|----------|-----------|--------|--------|--------------|
| 🇺🇸 Iowa | $3,292 | $2,270 | **$1,440** | **56.2%** ✅ |
| 🇺🇸 N. Virginia | $3,292 | $2,270 | **$1,440** | **56.2%** ✅ |
| 🇳🇱 Netherlands | $3,614 | $2,489 | $1,591 | 56.0% |
| 🇸🇬 Singapore | $3,942 | $2,716 | $1,737 | 55.9% |
| 🇮🇳 Delhi | $4,263 | $2,949 | $1,877 | 56.0% |

**Best Price:** Iowa/N. Virginia 3Y = $1,440/mo
**Worst Price:** Delhi On-Demand = $4,263/mo (196% more expensive)

### All Machine Types - 3-Year Commitment Pricing

| Machine Type | Iowa/VA | Delhi | Netherlands | Singapore |
|--------------|---------|-------|-------------|-----------|
| **g4-standard-48** | $1,440 | $1,877 | $1,591 | $1,737 |
| **g4-standard-96** | $2,890 | $3,760 | $3,176 | $3,468 |
| **g4-standard-192** | $5,782 | $7,512 | $6,358 | $6,935 |
| **g4-standard-384** | $11,563 | $15,023 | $12,717 | $13,878 |

---

## Key Insights

### 1. Consistent 56% Savings Worldwide
**All regions offer exactly 56% discount** with 3-year commitments across CPU, RAM, and GPU.

### 2. Regional Pricing Hierarchy (On-Demand)
1. **Iowa & N. Virginia**: Cheapest (baseline 100%)
2. **Netherlands**: +9.8% premium
3. **Singapore**: +19.7% premium
4. **Delhi**: +29.5% premium (most expensive)

### 3. Break-Even Analysis (g4-standard-48, Iowa)
- **Monthly Savings (3Y):** $1,852/month vs on-demand
- **Annual Savings:** $22,225/year
- **3-Year Total Savings:** $66,672

### 4. When to Use Each Commitment

| Commitment | Use When | Example |
|-----------|----------|---------|
| **3-Year** | Stable 24/7 workloads | Production ML training |
| **1-Year** | Growing workloads | Startup scaling up |
| **On-Demand** | Experimental/burst | PoC, development |

---

## Data Sources

- **Source:** Google Cloud SKU Pricing Database
- **Accuracy:** 100% verified from official SKUs
- **Date:** October 29, 2025
- **Method:** Direct SKU data, no estimations

**All pricing confirmed for:**
- 5 regions (Iowa, N. Virginia, Delhi, Netherlands, Singapore)
- 3 commitment types (On-Demand, 1-Year, 3-Year)
- 3 components (CPU, RAM, GPU RTX 6000 96GB)

---

## Changelog

| Version | Date | Changes |
|---------|------|---------|
| 2.0 | 2025-10-29 | Complete rewrite with accurate SKU data |
| 1.0 | 2025-10-29 | Initial version |

---

**Last Updated:** October 29, 2025
**Status:** Verified and Complete
