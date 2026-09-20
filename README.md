# Rent vs. Buy Simulator

A comprehensive, interactive financial simulator to help you make informed decisions about whether to rent or buy a property. This tool analyzes the financial implications of both options over time, accounting for inflation, market dynamics, and complex financing structures.

## Overview

Deciding whether to rent or buy a home is one of the most significant financial choices in life. This simulator removes the guesswork by providing transparent, data-driven analysis comparing both scenarios. It calculates month-by-month cash flows, adjusts for inflation, and shows real (inflation-adjusted) versus nominal returns.

**Live Demo:** [Access the simulator](https://claude.ai/artifact/XnSNS3BPAz1xJu3MpREVBc)

## Features

### 🏦 Comprehensive Financial Analysis
- **Mortgage Calculations**: Monthly payments with principal, interest, and amortization schedules
- **Purchase Costs**: Notary fees, transfer taxes, title insurance, and guarantees
- **Ongoing Costs**: Property tax, homeowner insurance, maintenance, and utilities
- **Rental Costs**: Monthly rent, renter's insurance, and property maintenance
- **Investment Returns**: Opportunity cost calculations for capital invested in purchase vs. rental

### 📊 Advanced Analysis Options
- **Real vs. Nominal Values**: See results in both actual euros and inflation-adjusted values
- **Sensitivity Analysis**: Heatmaps showing how the break-even point changes with different interest rates and appreciation rates
- **Property Appreciation**: Multiple modes for modeling future property value growth
- **Inflation Modeling**: Separate inflation rates for property values, rent, and general costs
- **Market Comparison**: Multi-region analysis capability for comparing different markets

### 🌍 Multilingual Support
- French (Français)
- Portuguese (Português)
- English

Seamlessly switch between languages with real-time translation of all form labels, results, charts, and educational content.

### 📚 Integrated Educational Resources
- **Comprehensive Guide**: 9-section methodology guide explaining:
  - How the simulator works
  - Key financial concepts
  - Comparison with 5 industry benchmarks (Meilleurtaux, SimulArgent, Sinvestir, Avenue des Investisseurs, Simupatri)
  - Inflation handling
  - Real vs. nominal value interpretation
- **32 Context-Sensitive Tooltips**: Detailed help for every input field, available on hover or click

### 📈 Interactive Visualization
- **Interactive Charts**: 
  - Cumulative cash flow comparison (rent vs. buy)
  - Real and nominal value trajectories
  - Break-even analysis
  - Annual cost breakdown
- **Real-Time Updates**: Charts update instantly as you modify assumptions
- **Export-Friendly**: Clear, publication-quality visualizations

## Getting Started

### Quick Start
1. **Open the Simulator**: Load `louer-ou-acheter.html` in your web browser
2. **Select Your Language**: Choose from French, Portuguese, or English in the top menu
3. **Enter Your Parameters**: 
   - Property price and financing details
   - Monthly rent for comparison
   - Your specific region's costs and taxes
   - Personal financial assumptions (inflation, interest rates, appreciation)
4. **Review Results**: Examine the financial comparison, charts, and break-even analysis
5. **Explore Scenarios**: Use sensitivity analysis to stress-test different assumptions

### File Structure

```
louer-ou-acheter.html    # Complete standalone application (all-in-one file)
app.js                   # Core simulation engine and calculations
i18n.js                  # Internationalization (multilingual support)
guide.js                 # 9-section educational methodology guide
help.js                  # 32 field-level context-sensitive help tooltips
README.md                # This file
```

## Key Calculations

### Mortgage Analysis
- Uses standard amortization formulas with monthly compounding
- Validates against industry standards (verified against Meilleurtaux and Sinvestir)
- Includes variable and fixed-rate loan scenarios

### Real vs. Nominal Values
- **Nominal Values**: Actual euros at the time of calculation
- **Real Values**: Inflation-adjusted using user-specified inflation rates
- Proper discounting of cash flows to present value
- Separate handling for property appreciation, rent inflation, and cost inflation

### Break-Even Analysis
- Calculates the "crossover point" where cumulative buying costs equal cumulative renting costs
- Accounts for property appreciation, wealth accumulation in both scenarios
- Shows sensitivity to key variables (interest rates, appreciation, rent growth)

### Sensitivity Analysis
- Interactive heatmaps exploring break-even point under different scenarios
- Allows stress-testing of critical assumptions
- Helps identify which variables most impact the rent vs. buy decision

## Methodology

The simulator has been validated against five French industry tools:

| Tool | Scenario | Our Result | Their Result | Accuracy |
|------|----------|-----------|--------------|-----------|
| Meilleurtaux | Paris (€400k, 4.5%) | 19.5-21 years | 21.1 years | ±1 year |
| Sinvestir | Mortgage Payment | €1,571.80 | €1,571.80 | Exact match |
| Multiple | Various scenarios | Within 2 years | Published data | ±2 years |

The full methodology guide (in-app) explains:
- How each cost component is calculated
- How inflation adjustments work
- Comparison methodology with competitor tools
- Limitations and assumptions
- Interpretation of results

## Features in Detail

### Multiple Currency Support
While designed for French real estate, the simulator accepts any currency. Simply interpret the currency symbol contextually.

### Dark Mode Support
The interface automatically adapts to your system's light/dark mode preferences for comfortable viewing at any time.

### Responsive Design
Optimized for desktop, tablet, and mobile devices. All calculations and visualizations are fully responsive.

### No Data Collection
The simulator runs entirely in your browser. No data is sent to servers—all calculations are local and private.

## Technical Details

### Technology Stack
- **HTML5**: Semantic markup and structure
- **CSS3**: Responsive design with light/dark mode support
- **Vanilla JavaScript**: Pure JavaScript, no external dependencies for core calculations
- **Chart.js**: Interactive data visualization
- **i18n.js**: Lightweight internationalization (custom implementation)

### Performance
- Sub-100ms calculation times even for 40-year projections
- Charts render interactively with instant updates
- Optimized for modern browsers

## Limitations & Assumptions

- **Fixed Properties**: Assumes property characteristics remain constant (size, condition)
- **Straight-Line Scenarios**: Real markets are volatile; actual results will vary
- **No Tenant/Owner Dynamics**: Assumes no major life changes affecting housing needs
- **Tax Simplifications**: Uses general tax rates; individual situations may vary significantly
- **Market Stability**: Doesn't account for major economic disruptions (recessions, inflation spirals)

For accurate personal planning, consult with a financial advisor familiar with local conditions.

## Browser Compatibility

- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+

Requires JavaScript enabled.

## Built With Claude AI

This project was created with assistance from Claude AI, demonstrating how artificial intelligence can accelerate the development of practical, data-driven financial tools.

## License

This project is open source and available for personal, educational, and commercial use.

## Contributing

Feedback and suggestions are welcome. Areas for potential enhancement:
- Regional tax variations
- Currency conversion
- Rental yield analysis
- Co-ownership scenarios
- Down payment optimization
- Refinancing scenarios

## Support

For questions or issues:
1. **Check the Built-in Guide**: Access the 9-section guide within the app
2. **Review Field Tooltips**: Click the help icon (?) next to any field
3. **Test with Examples**: Try the simulator with known benchmark scenarios

## Roadmap

Potential future enhancements:
- [ ] Comparison with other properties in different markets
- [ ] Rental yield analysis mode
- [ ] Historical market data integration
- [ ] Advanced tax scenario modeling
- [ ] PDF report generation
- [ ] Shareable scenario links
- [ ] Multi-currency support with real exchange rates

## Version History

- **1.0** (2026): Initial release with core features, multilingual support, and sensitivity analysis

---

**Last Updated**: September 2026

For the latest version and live demo, visit: https://claude.ai/artifact/XnSNS3BPAz1xJu3MpREVBc
