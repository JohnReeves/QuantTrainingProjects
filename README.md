# QuantTrainingProjects
A personal training ground for developing quantitative finance skills in
* C++ (pricing models)
* Python (data + risk)
* Excel (validation)

A plan that may be followed capriciously

```
quant-training-projects/
│
├── README.md                  # Overview of repo, learning goals
├── LICENSE                    # Choose MIT or Apache 2.0 (optional)
├── .gitignore                 # Ignore build/IDE files
│
├── cpp/                       # C++ projects (CLion + Eigen)
│   ├── CMakeLists.txt
│   ├── black_scholes/
│   │   ├── include/           # Header files
│   │   │   └── black_scholes.hpp
│   │   ├── src/               # Implementation
│   │   │   └── black_scholes.cpp
│   │   ├── tests/             # Unit tests (GoogleTest or Catch2)
│   │   │   └── test_black_scholes.cpp
│   │   └── CMakeLists.txt
│   │
│   ├── greeks/
│   │   ├── include/
│   │   ├── src/
│   │   ├── tests/
│   │   └── CMakeLists.txt
│   │
│   └── monte_carlo/
│       ├── include/
│       ├── src/
│       ├── tests/
│       └── CMakeLists.txt
│
├── python/                    # Python projects
│   ├── data_download/
│   │   ├── yfinance_test.py
│   │   ├── option_chain_plot.py
│   │   └── requirements.txt
│   │
│   ├── payoff_diagrams/
│   │   ├── straddle.py
│   │   ├── spreads.py
│   │   └── requirements.txt
│   │
│   └── risk_dashboard/
│       ├── dashboard.py
│       ├── utils.py
│       └── requirements.txt
│
├── excel/                     # Excel/CSV validation tools
│   ├── black_scholes_validation.xlsx
│   ├── greeks_heatmap.xlsx
│   └── sample_portfolio.csv
│
├── docs/                      # Learning notes & reports
│   ├── 01_black_scholes.md
│   ├── 02_greeks.md
│   ├── 03_binomial_mc.md
│   ├── 04_vol_surface.md
│   └── 05_risk_dashboard.md
│
└── training_schedule.md       # The long-term roadmap
```


