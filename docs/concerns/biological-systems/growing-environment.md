---
hide:
  - toc
---

# <i class="fa-solid fa-cloud-sun" style="font-size:20px"></i> Growing Environment

[TOC]


The root zone (rhizosphere) and aerial conditions (microclimate) that constitute the physical-chemical-biological context where plants grow.

## Growing Environment Transformation

Three-act narrative for growing environment management evolution.

1. Growing environments have historically relied on peat-based substrates with limited real-time monitoring, creating blind spots in root zone management and unsustainable dependence on finite peat resources.
2. IoT sensor networks, peat-free substrate formulation, and rhizosphere microbiome science enable evidence-based growing environment management with continuous feedback and sustainable material sourcing.
3. Predictively managed environments achieve stable growing conditions, reduced resource consumption, and enhanced plant-microbe interactions while eliminating peat dependence and minimising environmental footprint.

**Further Reading**

- [Barrett, G.E. et al. (2025) (Barrett, G.E. et al., 2025)](../../references.md#barrett-g-e-et-al-2025)
- [Xu, L. et al. (2023) (Xu, L. et al., 2023)](../../references.md#xu-l-et-al-2023)
- [Singh, A. et al. (2025) (Singh, A. et al., 2025)](../../references.md#singh-a-et-al-2025)


## Related Concerns

- supports: [Plant Health & Development](plant-health-development.md)
- managed by: [Water-Energy-Nutrient Nexus](../production-operations/resource-management.md)
- provided by: [CEA System Design](../production-operations/production-system-architecture.md)

## States

### 1. Characterized

Physical and chemical properties of substrate/soil and atmospheric conditions measured and documented.

**Checklist:**

- [ ] pH and EC measured: pH and electrical conductivity (EC) measured regularly using calibrated meters
- [ ] Texture and structure analyzed: Texture and structure analyzed (particle size distribution, aggregate stability, bulk density)
- [ ] Nutrient content assessed: Nutrient content assessed through soil/substrate testing (N, P, K, Ca, Mg, micronutrients)
- [ ] Temperature and humidity logged: Temperature and humidity logged continuously or at critical times (daily min/max, VPD)
- [ ] Light quantified: Light intensity and spectrum quantified (PPFD, DLI, R:FR ratio)
- [ ] Indigenous microbial community profiled: Indigenous microbial community composition profiled through culture-based or molecular methods.
- [ ] Pathogen risk of substrates assessed: Pathogen risk associated with substrate materials assessed, particularly oomycete contamination in organic peat alternatives.

**Progressed by:**

- [Characterise and Formulate Growing Media](../../activities/biological-systems/establish-manage-growing-environments/characterise-and-formulate-growing-media.md)
- [Monitor Root Zone and Aerial Environment](../../activities/biological-systems/establish-manage-growing-environments/monitor-root-zone-and-aerial-environment.md)

**Evidenced by:**

- [Growing Media Specification](../../work-products/growing-media-specification.md) — [Component List](../../work-products/growing-media-specification.md#1-component-list)
- [Environmental Monitoring Dashboard](../../work-products/environmental-monitoring-dashboard.md) — [Parameter Log](../../work-products/environmental-monitoring-dashboard.md#1-parameter-log)

### 2. Prepared

Growing media formulated or amended and site conditions modified to support target crop requirements.

**Checklist:**

- [ ] Substrate recipe selected: Substrate recipe selected based on crop requirements (drainage, aeration, water-holding capacity)
- [ ] Organic matter incorporated: Organic matter incorporated to improve soil structure and microbial activity
- [ ] Drainage established: Drainage systems established to prevent waterlogging and root anoxia
- [ ] pH adjusted: pH adjusted using lime (to raise) or sulfur (to lower) based on crop requirements
- [ ] Microclimate stabilized: Microclimate stabilized through windbreaks, shade structures, or thermal mass
- [ ] Beneficial microbial inoculants applied: Beneficial microbial inoculants applied where evidence supports their contribution to crop performance.
- [ ] Growing environment verified before planting: Growing environment verified against crop-specific requirements before planting with documented sign-off.

**Progressed by:**

- [Characterise and Formulate Growing Media](../../activities/biological-systems/establish-manage-growing-environments/characterise-and-formulate-growing-media.md)
- [Implement Peat-Free Growing Media Transition](../../activities/biological-systems/establish-manage-growing-environments/implement-peat-free-growing-media-transition.md)

**Evidenced by:**

- [Growing Media Specification](../../work-products/growing-media-specification.md) — [Physical and Chemical Profile](../../work-products/growing-media-specification.md#2-physical-and-chemical-profile)
- [Nutrient Management Plan](../../work-products/nutrient-management-plan.md) — [Fertiliser Schedule](../../work-products/nutrient-management-plan.md#1-fertiliser-schedule)

### 3. Balanced

Water-holding capacity, structural aeration, and nutrient availability optimized to prevent deficiencies or toxicities.

**Checklist:**

- [ ] Moisture retention adequate: Moisture retention adequate for crop needs without waterlogging (field capacity, permanent wilting point)
- [ ] Root oxygenation sufficient: Root oxygenation sufficient (air-filled porosity >10-20% depending on species)
- [ ] Nutrient ratios appropriate: Nutrient ratios appropriate (N:P:K balance, Ca:Mg ratio, micronutrient availability)
- [ ] Salt accumulation prevented: Salt accumulation prevented through leaching, substrate replacement, or precision fertigation
- [ ] Microbial activity healthy: Microbial activity healthy (respiration rates, decomposition, beneficial organism populations)
- [ ] Peat-free substrates validated: Peat-free or peat-reduced substrate blends demonstrate equivalent or superior plant performance.
- [ ] C:N ratio stabilised: Carbon-to-nitrogen ratio of organic substrates stabilised preventing nitrogen immobilisation or phytotoxic release.

**Progressed by:**

- [Characterise and Formulate Growing Media](../../activities/biological-systems/establish-manage-growing-environments/characterise-and-formulate-growing-media.md)
- [Implement Peat-Free Growing Media Transition](../../activities/biological-systems/establish-manage-growing-environments/implement-peat-free-growing-media-transition.md)

**Evidenced by:**

- [Growing Media Specification](../../work-products/growing-media-specification.md) — [Performance-Validated Formulation](../../work-products/growing-media-specification.md#3-performance-validated-formulation)
- [Nutrient Management Plan](../../work-products/nutrient-management-plan.md) — [Responsive Nutrition Programme](../../work-products/nutrient-management-plan.md#2-responsive-nutrition-programme)

### 4. Monitored

Continuous measurement of environmental parameters enables real-time assessment of suitability.

**Checklist:**

- [ ] Sensors deployed: Sensors deployed measuring soil moisture, temperature, EC, and atmospheric conditions
- [ ] Data captured continuously: Data captured continuously and transmitted to centralized platforms (cloud/local server)
- [ ] Thresholds defined: Thresholds defined for acceptable ranges triggering alerts when exceeded
- [ ] Alerts configured: Alerts configured for critical events (extreme temperatures, low moisture, high EC)
- [ ] Trends analyzed: Trends analyzed to identify gradual drift or seasonal patterns requiring intervention
- [ ] Non-destructive root zone assessment deployed: Non-destructive root zone assessment techniques provide nutrient uptake pattern information.
- [ ] Multi-cycle monitoring records retained: Environmental monitoring records retained for minimum three production cycles supporting trend analysis.

**Progressed by:**

- [Monitor Root Zone and Aerial Environment](../../activities/biological-systems/establish-manage-growing-environments/monitor-root-zone-and-aerial-environment.md)

**Evidenced by:**

- [Environmental Monitoring Dashboard](../../work-products/environmental-monitoring-dashboard.md) — [Automated Data Stream](../../work-products/environmental-monitoring-dashboard.md#2-automated-data-stream)

### 5. Dynamically Controlled

Automated systems adjust conditions in response to sensor feedback and crop requirements.

**Checklist:**

- [ ] Controllers programmed: Controllers programmed with setpoints and control logic (PID loops, fuzzy logic, rule-based)
- [ ] Actuators respond automatically: Actuators respond automatically (irrigation valves, HVAC dampers, supplemental lighting)
- [ ] Setpoints adaptive: Setpoints adaptive to growth stage, weather forecasts, or plant stress indicators
- [ ] Feedback loops tuned: Feedback loops tuned to minimize oscillation and maintain stability
- [ ] System stability maintained: System stability maintained despite external disturbances (weather, equipment faults)
- [ ] In-planta sensor feedback integrated: Wearable or in-planta sensor technologies provide direct physiological feedback from crop to control system.
- [ ] Manual override protocols established: Override protocols ensure safe manual intervention when automated systems encounter uncalibrated conditions.

**Progressed by:**

- [Monitor Root Zone and Aerial Environment](../../activities/biological-systems/establish-manage-growing-environments/monitor-root-zone-and-aerial-environment.md)

**Evidenced by:**

- [Nutrient Management Plan](../../work-products/nutrient-management-plan.md) — [Precision Nutrition Protocol](../../work-products/nutrient-management-plan.md#3-precision-nutrition-protocol)

### 6. Predictively Managed

AI-driven forecasting enables proactive environmental modification before stress manifests.

**Checklist:**

- [ ] Predictive models validated: Predictive models validated using historical data and crop response trials
- [ ] Historical data leveraged: Historical environmental and crop performance data leveraged for model training
- [ ] Weather integrated: Weather forecasts integrated to anticipate irrigation needs, heat stress, or frost risk
- [ ] Plant responses forecasted: Plant physiological responses forecasted (growth rate, water use, nutrient uptake)
- [ ] Preemptive adjustments executed: Preemptive adjustments executed (irrigation scheduling, pre-cooling, pre-heating)
- [ ] Rhizosphere microbiome management proactive: Rhizosphere microbiome management anticipates microbial community shifts and proactively adjusts inputs.
- [ ] Microbe-sensor integration deployed: Microbe-sensor integration platforms combine biological and digital monitoring for predictive management.

**Progressed by:**

- [Monitor Root Zone and Aerial Environment](../../activities/biological-systems/establish-manage-growing-environments/monitor-root-zone-and-aerial-environment.md)

**Evidenced by:**

- [Growing Media Specification](../../work-products/growing-media-specification.md) — [Lifecycle-Managed Substrate Standard](../../work-products/growing-media-specification.md#4-lifecycle-managed-substrate-standard)
- [Environmental Monitoring Dashboard](../../work-products/environmental-monitoring-dashboard.md) — [Predictive Analytics Platform](../../work-products/environmental-monitoring-dashboard.md#3-predictive-analytics-platform)
