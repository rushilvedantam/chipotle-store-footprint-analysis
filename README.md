# Chipotle Store Footprint Analysis

A geospatial analysis of Chipotle's U.S. store locations, identifying the strategic logic behind where the company has expanded. Built for CIS 406 (AI Foundations in Business) at Arizona State University, April 2026.

## Overview

Using a clean dataset of Chipotle's U.S. store locations, this project investigates whether Chipotle's growth follows a deliberate geographic strategy — and what that strategy reveals about how the company balances market saturation against new expansion.

## Data

- **Size:** 2,629 stores across 48 states
- **Fields:** State, City, Latitude, Longitude
- Fully clean geospatial data — no missing coordinates or state/city mismatches

## Bottom Line Up Front

Chipotle's footprint is concentrated, urban-centric, and Midwest-anchored — a strategy focused on dominating high-density markets rather than evenly expanding nationwide.

## Key Insights

**1. Stores are highly concentrated**
California (421 stores) far outpaces Texas (226) and Ohio (193). This signals a deliberate focus on high-value states, with signs of approaching saturation in the strongest markets.

**2. Expansion is urban-driven, not geographically even**
Most cities have exactly one Chipotle location, while a small number of cities have many. Dense city coverage is prioritized over broad geographic spread — Chipotle goes deep before it goes wide.

**3. The network is Midwest-centered**
The average store location sits near the geographic center of the U.S., suggesting a balance between national reach and logistics/supply chain efficiency.

## Strategic Takeaway

Chipotle grows by owning key markets and cities first, which leaves clear, targeted expansion opportunities in underpenetrated regions rather than a need for broad nationwide rollout.

## Tools

Python, pandas, geospatial plotting (matplotlib/plotly), data visualization
