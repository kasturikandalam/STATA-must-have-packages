# Stata Essential Packages Installation Script

A comprehensive collection of user-written Stata packages for econometrics, data analysis, and visualization. This repository provides a one-click installation script for all the packages you'll commonly need.

## 🚀 Quick Start

1. Download the `.do` file
2. Open Stata
3. Run the script:
   ```stata
   do "path/to/stata_packages_install.do"
   ```

That's it! All packages will be automatically installed.

## 📦 What's Included

### Core Regression & Output Tools
Essential packages for running regressions and exporting results:
- **estout** - Publication-quality regression tables
- **outreg2** - Export regression results to Word/Excel/LaTeX
- **asdoc** - Create Word-formatted tables
- **reghdfe** - High-dimensional fixed effects regression
- **ivreg2** / **ivreghdfe** - Instrumental variables regression
- **coefplot** - Visualize regression coefficients
- **winsor2** - Winsorize data to handle outliers

### Data Handling & Cleaning
Tools to make data wrangling easier:
- **gtools** - Faster versions of common Stata commands
- **missings** - Comprehensive missing value utilities
- **distinct** - Count distinct values
- **carryforward** - Fill missing values with previous observations
- **egenmore** - Additional egen functions
- **unicode** - Handle Unicode text encoding

### Visualization
Create publication-ready graphs:
- **binscatter** - Binned scatter plots
- **coefplot** - Coefficient plots
- **heatplot** - Heat maps
- **grc1leg2** - Combine graphs with single legend
- **schemepack** - Beautiful color schemes
- **spmap** - Spatial maps

### Advanced Econometrics
Specialized econometric methods:
- **rdrobust** - Regression discontinuity design
- **csdid** / **did_imputation** / **eventstudyinteract** - Difference-in-differences with staggered treatment
- **xtabond2** - Dynamic panel data (Arellano-Bond)
- **psmatch2** / **nnmatch** - Propensity score matching
- **boottest** - Wild bootstrap for cluster-robust inference
- **xtscc** - Panel data with Driscoll-Kraay standard errors
- **weakivtest** - Test for weak instruments

### Workflow & Productivity
Streamline your research workflow:
- **project** - Manage project dependencies
- **texdoc** - Create LaTeX documents from Stata
- **markstat** - Markdown + Stata integration
- **fs** - File system utilities
- **filelist** - Generate lists of files

### Utility Packages
Miscellaneous useful tools:
- **kountry** - Standardize country names
- **wbopendata** - Access World Bank data directly
- **dataverse** - Access Dataverse repositories
- **randtreat** - Random treatment assignment

### Fun Packages 🎉
Because coding should be enjoyable:
- **dadjoke** - Random dad jokes
- **motivate** - Motivational quotes
- **haiku** - Random haikus
- **reggae_music** - Plays reggae (yes, really!)
- **nicewords** - Compliments from Stata

## 📋 Requirements

- Stata 14 or later (some packages may require newer versions)
- Internet connection for downloading packages from SSC
- Approximately 5-10 minutes for complete installation

## 🤝 Contributing

Compiled by:
- Kasturi Kandalam

Feel free to suggest additional packages or improvements via pull requests!

## 📚 Resources

- [Stata SSC Archive](https://ideas.repec.org/s/boc/bocode.html) - Browse all available packages
- [Stata Documentation](https://www.stata.com/features/documentation/)
- [Stata Forums](https://www.statalist.org/) - Get help from the community

## ⚠️ Notes

- The `replace` option ensures packages are updated if already installed
- Some packages are dependencies for others (e.g., ftools for reghdfe)
- Installation time varies based on internet speed
- All packages are from SSC (vetted by StataCorp)

## 📝 License

This installation script is provided as-is for educational and research purposes. Individual packages maintain their own licenses.

---

**Pro tip**: After installation, try running `motivate` and the `demotivate` in Stata for a smile while your regressions run! 😄
