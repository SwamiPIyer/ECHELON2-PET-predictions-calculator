# ECHELON-2 Clinical Decision Dashboard

An evidence-based clinical decision support tool for peripheral T-cell lymphoma (PTCL) treatment selection, risk assessment, and PET response prediction based on the ECHELON-2 trial data.

## Overview

This interactive dashboard provides clinicians with comprehensive tools for PTCL patient management, including:

- **Risk Stratification**: IPI and PIT prognostic model calculators with validated survival data
- **PET Response Prediction**: PET4 response prediction based on treatment arm, histology, and clinical parameters
- **Treatment Outcomes**: Evidence-based outcome predictions comparing A+CHP vs CHOP
- **Trial Results**: Complete ECHELON-2 statistical analysis with hazard ratios and significance testing
- **Clinical Analytics**: Patient demographics and subtype-specific outcome visualizations

## Features

### Risk Assessment
- Toggle between IPI (International Prognostic Index) and PIT (Prognostic Index for PTCL-U) models
- Real-time risk calculation with validated PTCL survival data
- Evidence-based prognostic categorization with 5-year and 10-year survival estimates

### PET Response Prediction
- Interactive PET4 response prediction incorporating:
  - Treatment arm selection (A+CHP vs CHOP)
  - Histological subtype (sALCL ALK+/ALK-, AITL, PTCL-NOS)
  - Baseline SUVmax values
  - Tumor bulk assessment
- Visual representation of predicted Deauville scores
- Prognostic impact analysis showing 38-45 percentage point survival differences

### Treatment Decision Support
- Subtype-specific outcome predictions
- Comparative efficacy analysis between treatment regimens
- Statistical significance testing with p-values and confidence intervals

## Clinical Evidence Base

### Primary References
- **ECHELON-2 Trial**: Horwitz S, et al. Lancet. 2019;393(10168):229-240
- **5-Year Results**: Horwitz S, et al. Ann Oncol. 2022;33(3):288-298
- **PET4 Analysis**: Iyer SP, et al. Blood Adv. 2025 (Epub ahead of print)
- **IPI Model**: International NHL Prognostic Factors Project. N Engl J Med. 1993;329:987-994
- **PIT Model**: Gallamini A, et al. Blood. 2004;103:2474-2479

### Key Clinical Findings
- 30% reduction in progression risk with A+CHP vs CHOP (HR 0.70, 95% CI 0.53-0.91)
- 28% reduction in death risk (HR 0.72, 95% CI 0.53-0.99)
- Significant benefit in sALCL patients, especially ALK+ subtype
- PET4-negative patients show substantially better outcomes regardless of treatment

## Usage

### For Clinicians
1. **Risk Assessment**: Input patient characteristics to calculate IPI or PIT scores with prognostic estimates
2. **Treatment Planning**: Use histology-specific outcome predictions to guide therapy selection
3. **PET Interpretation**: Predict PET4 response probabilities and understand prognostic implications
4. **Patient Counseling**: Access evidence-based survival data for informed consent discussions

### Technical Requirements
- Modern web browser with JavaScript enabled
- No installation required - runs entirely in browser
- Responsive design compatible with desktop, tablet, and mobile devices

## Data Sources

All calculations and predictions are based on peer-reviewed clinical trial data:
- ECHELON-2 trial (N=452 patients)
- Multinational, randomized, double-blind phase 3 study
- 5-year follow-up data with mature survival endpoints
- PET4 response analysis from recent Blood Advances publication

## Limitations

- Predictions based on clinical trial populations which may not represent all real-world patients
- AITL patients showed limited benefit and should be counseled accordingly
- Individual patient outcomes may vary from population-based predictions
- Tool intended for clinical decision support, not replacement of clinical judgment

## Installation

### GitHub Pages Deployment
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch" and choose `main` branch
4. Your dashboard will be available at `https://yourusername.github.io/repository-name`

### Local Usage
1. Download the `index.html` file
2. Open in any modern web browser
3. No server or additional setup required

## Contributing

Contributions are welcome for:
- Bug fixes and performance improvements
- Additional clinical validation data
- User interface enhancements
- Documentation improvements

Please ensure any contributions maintain clinical accuracy and include appropriate references.

## License

MIT License - See LICENSE file for details

## Disclaimer

This tool is intended for healthcare professionals and educational purposes only. It should not replace clinical judgment or established treatment protocols. All treatment decisions should be made by qualified healthcare providers in consultation with patients and based on individual clinical circumstances.

## Citation

If you use this tool in research or clinical practice, please cite:
```
ECHELON-2 Clinical Decision Dashboard [Computer software]. 
Available from: https://github.com/yourusername/echelon2-calculator
```

## Contact

For questions, suggestions, or clinical collaboration opportunities, please open an issue on GitHub or contact the repository maintainer.
