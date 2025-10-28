# G4 Instance Pricing Breakdown - Google Cloud Compute Engine
**Complete Cost Analysis by Location, Machine Type, and Commitment Level**

---

## Document Information
- **Date:** October 29, 2025
- **Source:** Google Cloud SKU Pricing Data
- **Currency:** USD
- **Effective Date:** October 28, 2025
- **Instance Family:** G4 (GPU-optimized with NVIDIA RTX 6000 96GB)

---

## Table of Contents
1. [Pricing Components](#pricing-components)
2. [Location 1: Iowa (US)](#location-1-iowa-us-central1---united-states)
3. [Location 2: Delhi (India)](#location-2-delhi-asia-south2---india)
4. [Location 3: Netherlands (EU)](#location-3-netherlands-europe-west4)
5. [Location 4: Singapore (APAC)](#location-4-singapore-asia-southeast1)
6. [Cost Comparison Summary](#cost-comparison-summary)
7. [Machine Type Specifications](#machine-type-specifications)
8. [Key Insights](#key-insights)

---

## Pricing Components

### **Confirmed Pricing from SKU File:**

**CPU:**
- **G4 Core (Iowa, us-central1)**: $0.048910/hour per vCPU

**RAM:**
- **G4 RAM (Delhi, asia-south2)**: $0.007631/hour per GB

**GPU (RTX 6000 96GB):**
- **Netherlands (3-Year Commitment)**: $0.530299/hour
- **Netherlands (1-Year Commitment)**: $0.831600/hour
- **Delhi (3-Year Commitment)**: $0.626717/hour
- **Singapore (1-Year Commitment)**: $0.907200/hour

**Estimated Pricing:**
- **On-Demand GPU**: ~$1.20-1.50/hour (typically 1.8-2.0x of 1-year commitment)
- **Regional Multipliers**: Iowa (base), Delhi (+8%), Netherlands (+8%), Singapore (+15%)

---

## Location 1: Iowa (us-central1) - United States

### **g4-standard-48** (48 vCPU, 180 GB RAM, 1 GPU)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly (730h) | Annual (8,760h) |
|------------|--------|--------|--------|----------|----------------|-----------------|
| **On-Demand** | $2.35 | $1.37 | $1.50¹ | **$5.22** | **$3,811** | **$45,729** |
| **1-Year** | $2.35 | $1.37 | $0.90² | **$4.62** | **$3,373** | **$40,471** |
| **3-Year** | $2.35 | $1.37 | $0.60² | **$4.32** | **$3,154** | **$37,843** |

### **g4-standard-96** (96 vCPU, 360 GB RAM, 2 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $4.70 | $2.75 | $3.00 | **$10.45** | **$7,629** | **$91,542** |
| **1-Year** | $4.70 | $2.75 | $1.80 | **$9.25** | **$6,753** | **$81,030** |
| **3-Year** | $4.70 | $2.75 | $1.20 | **$8.65** | **$6,315** | **$75,774** |

### **g4-standard-192** (192 vCPU, 720 GB RAM, 4 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $9.39 | $5.49 | $6.00 | **$20.88** | **$15,242** | **$182,909** |
| **1-Year** | $9.39 | $5.49 | $3.60 | **$18.48** | **$13,490** | **$161,885** |
| **3-Year** | $9.39 | $5.49 | $2.40 | **$17.28** | **$12,614** | **$151,373** |

### **g4-standard-384** (384 vCPU, 1,440 GB RAM, 8 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $18.78 | $10.99 | $12.00 | **$41.77** | **$30,492** | **$365,907** |
| **1-Year** | $18.78 | $10.99 | $7.20 | **$36.97** | **$26,988** | **$323,859** |
| **3-Year** | $18.78 | $10.99 | $4.80 | **$34.57** | **$25,236** | **$302,835** |

---

## Location 2: Delhi (asia-south2) - India

### **g4-standard-48** (48 vCPU, 180 GB RAM, 1 GPU)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly (730h) | Annual (8,760h) |
|------------|--------|--------|--------|----------|----------------|-----------------|
| **On-Demand** | $2.54³ | $1.37 | $1.50¹ | **$5.41** | **$3,949** | **$47,390** |
| **1-Year** | $2.54³ | $1.37 | $1.00⁴ | **$4.91** | **$3,584** | **$43,015** |
| **3-Year** | $2.54³ | $1.37 | $0.63 | **$4.54** | **$3,314** | **$39,769** |

### **g4-standard-96** (96 vCPU, 360 GB RAM, 2 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $5.09 | $2.75 | $3.00 | **$10.84** | **$7,913** | **$94,958** |
| **1-Year** | $5.09 | $2.75 | $2.00 | **$9.84** | **$7,183** | **$86,218** |
| **3-Year** | $5.09 | $2.75 | $1.25 | **$9.09** | **$6,636** | **$79,628** |

### **g4-standard-192** (192 vCPU, 720 GB RAM, 4 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $10.18 | $5.49 | $6.00 | **$21.67** | **$15,819** | **$189,828** |
| **1-Year** | $10.18 | $5.49 | $4.00 | **$19.67** | **$14,359** | **$172,348** |
| **3-Year** | $10.18 | $5.49 | $2.51 | **$18.18** | **$13,271** | **$159,348** |

### **g4-standard-384** (384 vCPU, 1,440 GB RAM, 8 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $20.35 | $10.99 | $12.00 | **$43.34** | **$31,638** | **$379,658** |
| **1-Year** | $20.35 | $10.99 | $8.00 | **$39.34** | **$28,718** | **$344,608** |
| **3-Year** | $20.35 | $10.99 | $5.01 | **$36.35** | **$26,536** | **$318,426** |

---

## Location 3: Netherlands (europe-west4)

### **g4-standard-48** (48 vCPU, 180 GB RAM, 1 GPU)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly (730h) | Annual (8,760h) |
|------------|--------|--------|--------|----------|----------------|-----------------|
| **On-Demand** | $2.64³ | $1.53³ | $1.66⁵ | **$5.83** | **$4,256** | **$51,077** |
| **1-Year** | $2.64 | $1.53 | $0.83 | **$5.00** | **$3,650** | **$43,800** |
| **3-Year** | $2.64 | $1.53 | $0.53 | **$4.70** | **$3,431** | **$41,172** |

### **g4-standard-96** (96 vCPU, 360 GB RAM, 2 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $5.28 | $3.06 | $3.33 | **$11.67** | **$8,519** | **$102,229** |
| **1-Year** | $5.28 | $3.06 | $1.66 | **$10.00** | **$7,300** | **$87,600** |
| **3-Year** | $5.28 | $3.06 | $1.06 | **$9.40** | **$6,862** | **$82,344** |

### **g4-standard-192** (192 vCPU, 720 GB RAM, 4 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $10.56 | $6.13 | $6.66 | **$23.35** | **$17,046** | **$204,546** |
| **1-Year** | $10.56 | $6.13 | $3.33 | **$20.02** | **$14,615** | **$175,375** |
| **3-Year** | $10.56 | $6.13 | $2.12 | **$18.81** | **$13,731** | **$164,775** |

### **g4-standard-384** (384 vCPU, 1,440 GB RAM, 8 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $21.12 | $12.25 | $13.31 | **$46.68** | **$34,076** | **$408,917** |
| **1-Year** | $21.12 | $12.25 | $6.65 | **$40.02** | **$29,215** | **$350,575** |
| **3-Year** | $21.12 | $12.25 | $4.24 | **$37.61** | **$27,455** | **$329,463** |

---

## Location 4: Singapore (asia-southeast1)

### **g4-standard-48** (48 vCPU, 180 GB RAM, 1 GPU)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly (730h) | Annual (8,760h) |
|------------|--------|--------|--------|----------|----------------|-----------------|
| **On-Demand** | $2.69³ | $1.62³ | $1.81⁶ | **$6.12** | **$4,468** | **$53,611** |
| **1-Year** | $2.69 | $1.62 | $0.91 | **$5.22** | **$3,811** | **$45,732** |
| **3-Year** | $2.69³ | $1.62³ | $0.60³ | **$4.91** | **$3,584** | **$43,015** |

### **g4-standard-96** (96 vCPU, 360 GB RAM, 2 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $5.38 | $3.24 | $3.63 | **$12.25** | **$8,943** | **$107,310** |
| **1-Year** | $5.38 | $3.24 | $1.81 | **$10.43** | **$7,614** | **$91,367** |
| **3-Year** | $5.38 | $3.24 | $1.21³ | **$9.83** | **$7,176** | **$86,111** |

### **g4-standard-192** (192 vCPU, 720 GB RAM, 4 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $10.75 | $6.48 | $7.26 | **$24.49** | **$17,878** | **$214,529** |
| **1-Year** | $10.75 | $6.48 | $3.63 | **$20.86** | **$15,228** | **$182,734** |
| **3-Year** | $10.75 | $6.48 | $2.42³ | **$19.65** | **$14,345** | **$172,134** |

### **g4-standard-384** (384 vCPU, 1,440 GB RAM, 8 GPUs)

| Commitment | CPU/hr | RAM/hr | GPU/hr | Total/hr | Monthly | Annual |
|------------|--------|--------|--------|----------|---------|---------|
| **On-Demand** | $21.50 | $12.96 | $14.52 | **$48.98** | **$35,755** | **$429,058** |
| **1-Year** | $21.50 | $12.96 | $7.26 | **$41.72** | **$30,456** | **$365,469** |
| **3-Year** | $21.50 | $12.96 | $4.84³ | **$39.30** | **$28,689** | **$344,268** |

---

## Cost Comparison Summary

### **g4-standard-48 - Monthly Costs by Location**

| Location | On-Demand | 1-Year Commit | 3-Year Commit | Savings (3Y vs OD) |
|----------|-----------|---------------|---------------|--------------------|
| **Iowa (US)** | $3,811 | $3,373 | $3,154 | **17.2%** |
| **Delhi (India)** | $3,949 | $3,584 | $3,314 | **16.1%** |
| **Netherlands (EU)** | $4,256 | $3,650 | $3,431 | **19.4%** |
| **Singapore (APAC)** | $4,468 | $3,811 | $3,584 | **19.8%** |

### **g4-standard-96 - Monthly Costs by Location**

| Location | On-Demand | 1-Year Commit | 3-Year Commit | Savings (3Y vs OD) |
|----------|-----------|---------------|---------------|--------------------|
| **Iowa (US)** | $7,629 | $6,753 | $6,315 | **17.2%** |
| **Delhi (India)** | $7,913 | $7,183 | $6,636 | **16.1%** |
| **Netherlands (EU)** | $8,519 | $7,300 | $6,862 | **19.4%** |
| **Singapore (APAC)** | $8,943 | $7,614 | $7,176 | **19.8%** |

### **g4-standard-192 - Monthly Costs by Location**

| Location | On-Demand | 1-Year Commit | 3-Year Commit | Savings (3Y vs OD) |
|----------|-----------|---------------|---------------|--------------------|
| **Iowa (US)** | $15,242 | $13,490 | $12,614 | **17.2%** |
| **Delhi (India)** | $15,819 | $14,359 | $13,271 | **16.1%** |
| **Netherlands (EU)** | $17,046 | $14,615 | $13,731 | **19.4%** |
| **Singapore (APAC)** | $17,878 | $15,228 | $14,345 | **19.8%** |

### **g4-standard-384 - Monthly Costs by Location**

| Location | On-Demand | 1-Year Commit | 3-Year Commit | Savings (3Y vs OD) |
|----------|-----------|---------------|---------------|--------------------|
| **Iowa (US)** | $30,492 | $26,988 | $25,236 | **17.2%** |
| **Delhi (India)** | $31,638 | $28,718 | $26,536 | **16.1%** |
| **Netherlands (EU)** | $34,076 | $29,215 | $27,455 | **19.4%** |
| **Singapore (APAC)** | $35,755 | $30,456 | $28,689 | **19.8%** |

---

## Machine Type Specifications

| Machine Type | vCPUs | Memory (GB) | GPUs | GPU Memory (GB) | Max Titanium SSD (GiB) | Physical NICs | Max Bandwidth (Gbps) |
|--------------|-------|-------------|------|-----------------|------------------------|---------------|---------------------|
| **g4-standard-48** | 48 | 180 | 1 | 96 | 1,500 | 1 | 50 |
| **g4-standard-96** | 96 | 360 | 2 | 192 | 3,000 | 1 | 100 |
| **g4-standard-192** | 192 | 720 | 4 | 384 | 6,000 | 1 | 200 |
| **g4-standard-384** | 384 | 1,440 | 8 | 768 | 12,000 | 2 | 400 |

**GPU Specifications:**
- **Model:** NVIDIA RTX 6000 (Ada Lovelace Architecture)
- **Memory per GPU:** 96 GB GDDR7
- **Memory Technology:** GDDR7 (latest generation)
- **Use Cases:** AI/ML training, inference, 3D rendering, scientific computing

---

## Key Insights

### **1. Cost Optimization**

**Best Value Locations (3-Year Commitment):**
1. **Delhi (India)**: Cheapest overall ($3,314/mo for g4-standard-48)
2. **Iowa (US)**: Second cheapest ($3,154/mo)
3. **Netherlands (EU)**: Mid-range ($3,431/mo)
4. **Singapore (APAC)**: Most expensive ($3,584/mo)

**Commitment Savings:**
- **3-Year Commitment**: Save 16-20% vs on-demand
- **1-Year Commitment**: Save 10-15% vs on-demand
- **Best ROI**: Netherlands and Singapore show highest % savings with commitments

### **2. Regional Pricing Patterns**

**Price Variance by Location:**
- **Lowest to Highest Spread**: ~17% difference (Delhi to Singapore)
- **US (Iowa)**: Baseline pricing, good balance
- **India (Delhi)**: Competitive pricing, good for Asia operations
- **EU (Netherlands)**: Premium pricing, GDPR compliance benefits
- **APAC (Singapore)**: Highest pricing, strategic location for Asia-Pacific

### **3. Cost Components**

**Breakdown for g4-standard-48 (On-Demand, Iowa):**
- **CPU**: $2.35/hr (45%)
- **RAM**: $1.37/hr (26%)
- **GPU**: $1.50/hr (29%)

**GPU represents 25-35% of total cost**, making commitment discounts on GPUs highly valuable.

### **4. Scaling Economics**

**Cost per vCPU (On-Demand, Iowa):**
- g4-standard-48: $0.109/vCPU/hour
- g4-standard-96: $0.109/vCPU/hour
- g4-standard-192: $0.109/vCPU/hour
- g4-standard-384: $0.109/vCPU/hour

**Linear scaling**: No bulk discount for larger instances, but better GPU:CPU ratio on larger machines.

### **5. Budget Planning**

**Annual Budget Requirements (3-Year Commitment, Delhi - Cheapest):**
- **g4-standard-48**: $39,769/year
- **g4-standard-96**: $79,628/year
- **g4-standard-192**: $159,348/year
- **g4-standard-384**: $318,426/year

### **6. Commitment Strategy Recommendations**

**When to use 3-Year Commitment:**
- Stable, long-term workloads
- Predictable capacity needs
- Budget-constrained projects
- **Save**: $657-$1,769/month (depending on location)

**When to use 1-Year Commitment:**
- Growing workloads with some uncertainty
- Testing production readiness
- Moderate risk tolerance
- **Save**: $438-$657/month vs on-demand

**When to use On-Demand:**
- Experimental workloads
- Burst computing needs
- Short-term projects (<6 months)
- High flexibility required

### **7. Regional Considerations**

**Iowa (US):**
- ✅ Good baseline pricing
- ✅ Central US location
- ✅ Low latency to North America
- ⚠️ Consider data residency requirements

**Delhi (India):**
- ✅ Lowest total cost
- ✅ Good for Asian markets
- ✅ Competitive advantage
- ⚠️ Check network latency requirements

**Netherlands (EU):**
- ✅ GDPR-compliant data residency
- ✅ Central European location
- ✅ Good for EU customers
- ⚠️ 11% premium over Delhi

**Singapore (APAC):**
- ✅ Strategic Asia-Pacific hub
- ✅ Low latency to Southeast Asia
- ✅ Excellent connectivity
- ⚠️ Highest cost (17% premium over Delhi)

---

## Footnotes

**¹** On-demand GPU pricing estimated at $1.50/hour based on typical 1.8-2.0x multiplier from 1-year commitment pricing

**²** Commitment pricing estimated based on typical Google Cloud discount rates:
- 1-Year Commitment: ~40% discount off on-demand
- 3-Year Commitment: ~60% discount off on-demand

**³** Estimated pricing using regional multipliers based on typical Google Cloud pricing patterns:
- India (Delhi): +8% from base
- Europe (Netherlands): +8% from base
- APAC (Singapore): +15% from base

**⁴** Delhi 1-year GPU commitment estimated at $1.00/hour (not explicitly in SKU file)

**⁵** Netherlands on-demand GPU pricing estimated at 2.0x the confirmed 1-year commitment price ($0.831600)

**⁶** Singapore on-demand GPU pricing estimated at 2.0x the confirmed 1-year commitment price ($0.907200)

---

## Additional Costs Not Included

This pricing analysis covers **compute costs only**. Additional costs may include:

1. **Storage:**
   - Titanium SSD (high-performance local storage)
   - Persistent Disks
   - Cloud Storage

2. **Network:**
   - Egress (outbound data transfer)
   - Inter-region data transfer
   - Load balancing

3. **Additional Services:**
   - Cloud Logging
   - Cloud Monitoring
   - Premium support
   - Security services

4. **Licensing:**
   - Third-party software licenses
   - GPU driver licenses (if applicable)

**Estimate**: Add 10-20% to compute costs for typical production workloads with moderate storage and network usage.

---

## Data Sources

- **Primary Source**: Google Cloud SKU pricing data file (`skus.json`)
- **Effective Date**: October 28, 2025
- **Confirmed Pricing Points**:
  - G4 Instance Core: Iowa (us-central1)
  - G4 Instance RAM: Delhi (asia-south2)
  - RTX 6000 96GB: Netherlands (1Y/3Y), Delhi (3Y), Singapore (1Y)
- **Estimation Method**: Regional multipliers and commitment discount patterns based on typical Google Cloud pricing structures

---

## Changelog

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2025-10-29 | Initial pricing breakdown created |

---

**Document Status:** Complete
**Next Review Date:** When Google Cloud updates G4 pricing
**Contact:** Cloud Infrastructure Team
**Last Updated:** October 29, 2025
