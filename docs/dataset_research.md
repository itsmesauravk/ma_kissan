# MA KISAAN — Dataset Research

## Primary Goal

Build a Nepal-focused crop recommendation and yield risk system using open data.

---

## Dataset 1: FAOSTAT Crop Yield

- Source: FAO (FAOSTAT)
- Country: Nepal
- Years: 2000–2023
- Crops: Rice, Maize, Wheat, Millet, Barley
- Features:
  - Crop
  - Year
  - Yield (kg/ha)
- License: Open (FAO)

---

## Dataset 2: Crop Recommendation Dataset (Kaggle)

- Source: Kaggle
- Features:
  - N, P, K
  - Temperature
  - Rainfall
  - Humidity
  - Crop label
- Use: Training baseline crop classifier
- Limitation: Not Nepal-specific

---

## Dataset 3: Climate Data

- Source: World Bank Open Data
- Features:
  - Avg annual rainfall
  - Avg temperature
- Region: Nepal

---

## Strategy

- FAOSTAT = Ground truth yields
- Kaggle = ML feature patterns
- Climate data = Regional adjustment

---

## Risks

- Limited soil data for Nepal
- Mitigation: Use proxy features and augmentation

## Primary Dataset Selected

- Name: District-wise Climate and Crop Data of Nepal
- Source: ICIMOD, OpenDataNepal, NASA MERRA-2
- Coverage:
  - Crop yield (1979–2014)
  - Daily climate data (district-level)
- Role:
  - Primary training dataset for MA KISAAN V1
