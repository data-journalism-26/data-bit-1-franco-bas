# After Russia, life’s a gas for American allies

**Data Bit 1 — Data Journalism**  
**Author:** Franco Bastida  
**Date:** May 2026  

---

This data story examines how the U.S. became the world’s dominant LNG exporter, how Russia’s invasion of Ukraine redirected those flows toward Europe, and why the resulting dependence is better understood as managed rather than absolute.

The piece combines U.S. Energy Information Administration (EIA) with a lightweight scrollytelling web layout.

## Core arguments

1. **U.S. LNG dominance was built structurally over decades** even before the Trump administration. 
2. **Russia’s invasion of Ukraine redirected LNG flows** to a handful of European countries.
3. **Energy dominance is still constrained by markets**, meaning it does not guarantee stability or geopolitical control.

---

## Technique

- **Programmatic work:** Python (`pandas`, `matplotlib`) for data cleaning, analysis, and chart production  
- **Web presentation:** HTML/CSS scrollytelling layout for GitHack  
- **Graphics:** SVG exports publication-style charts  
- **Design principles:** direct annotations, muted gridlines, categorical color hierarchy, stacked areas for market concentration, minimal visual clutter  

---

## Repository Structure

```text
├── index.html                 # article & web layout
├── README.md
├── lng-maps.ipynb             # data cleaning & visualization notebook
│
├── figures/
│   ├── lng_pipeline.svg       # LNG vs pipeline exports
│   ├── lng_europe.svg         # European LNG destinations
│   └── lng_shares.svg         # LNG export shares by region
│
└── data/
    └── lng-exports.xlsx 
```

---

## GitHack view

 **[Read the article here](https://raw.githack.com/data-journalism-26/data-bit-2-ashley-razo/main/index.html)**