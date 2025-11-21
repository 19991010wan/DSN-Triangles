# A Brief Introduction of DSN-Triangles

The data files consist of two parts: *RQ1* and *RQ2*.

In *RQ1*, the data for **Section 4.1** are provided:

- `DSN stability distribution.pdf` displays the distribution of DSN stability constructed from 197 projects.
- `DSN features distribution.pdf` shows the distribution of four network structural characteristics of the 197 DSNs (DSN Size, DSN Density, DSN Bridge, and DSN K-stars).
- `DSN_features_data.csv` presents the results of the non-parametric Spearman rank-order correlation test between the four DSN structural features and DSN stability.
- `project_features_data.csv` presents the results of the non-parametric Spearman rank-order correlation test and the Kruskal-Wallis rank sum test between project features and DSN stability.
  - Column 1: Project Repo Name
  - Column 2: DSN Stability
  - Columns 3-12: Main Programming Language (C++, Ruby, Python, Go, C, Java, JavaScript-like, PHP, other language)
  - Columns 13-21: Application Domain (System, Cloud & Networking, Security & Privacy, Development Environment & Tools, AI, Data Science, Enterprise-General, Mobile, other domain)
  - Column 22: Sponsorship
  - Column 23: Project Size
  - Column 24: Average Experience

- The `stability_trends_picture` folder contains 197 charts. Each chart illustrates the month-by-month stability trend over 36 consecutive months for a single project.

In *RQ2*, the data for **Section 4.2** are provided:

- `regression_data.csv` shows the values used for the regression model.
  - Column 1: Project Repo Name
  - Columns 2-5: Project Outcome Variables (NewC, BCT, NewB, BFR)
  - Column 6: DSN Stability
  - Columns 7-10: Four DSN Structural Features
  - Columns 11-20: Main Programming Language
  - Columns 21-29: Application Domain
  - Column 30: Sponsorship
  - Column 31: Project Size
  - Column 32: Average Experience

- `time_related_effect.pdf` displays the time-fixed effects tests of DSN stability and the four project outcome variables.













<iframe id="intercom-frame" aria-hidden="true" tabindex="-1" title="Intercom" style="color: rgb(128, 0, 128); font-family: quote-cjk-patch, Inter, system-ui, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Roboto, Oxygen, Ubuntu, Cantarell, &quot;Open Sans&quot;, &quot;Helvetica Neue&quot;, sans-serif; font-size: 14px; font-style: normal; font-variant-ligatures: no-contextual; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; pointer-events: none; position: absolute !important; opacity: 0 !important; width: 1px !important; height: 1px !important; top: 0px !important; left: 0px !important; border: none !important; display: block !important; z-index: -1 !important;"></iframe>