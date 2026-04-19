# 🔮 Thais Karoline — Portfolio

> **Data Engineer · Full Stack · Azure · Databricks · Python · SQL**  
> Live demo: [thaiskaroline.dev](https://thaiskaroline.dev) · [LinkedIn](https://linkedin.com/in/thaiskaroline) · [GitHub](https://github.com/thaiskaroline)

---

<div align="center">

![Data Engineer](https://img.shields.io/badge/Data_Engineer-Azure_Databricks-FF2D95?style=flat-square)
![Python](https://img.shields.io/badge/Python-Expert-7C3AED?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Advanced-FF2D95?style=flat-square)
![Remote](https://img.shields.io/badge/Remote-EOR_Eligible-34d399?style=flat-square)
![Toyota](https://img.shields.io/badge/Toyota-2+_Years-FF2D95?style=flat-square)

</div>

---

## 🚀 About This Portfolio

Cyberpunk-aesthetic portfolio showcasing **Data Engineering** and **Full Stack** work, with a live interactive **Holt-Winters demand forecasting** demo. Built to demonstrate enterprise-grade engineering to international recruiters.

**Key highlights from the portfolio:**
- 40% processing time reduction via Azure Databricks migration @ Toyota
- 70% operational automation via Python pipelines
- Live Holt-Winters + Ridge + GBM ensemble forecasting demo
- Interactive SQL Server-integrated demand prediction system

---

## 🛠 Tech Stack

### Data Engineering (Primary)
| Tool | Proficiency | Used at |
|---|---|---|
| Azure Databricks | ⭐⭐⭐⭐⭐ | Toyota |
| PySpark | ⭐⭐⭐⭐ | Toyota |
| SQL (T-SQL, PostgreSQL) | ⭐⭐⭐⭐⭐ | Toyota + Projects |
| ETL/ELT Pipelines | ⭐⭐⭐⭐⭐ | Toyota |
| SAP Integration | ⭐⭐⭐⭐ | Toyota |
| Power BI + DAX | ⭐⭐⭐⭐⭐ | Toyota |
| dbt | ⭐⭐⭐ | Projects |
| Apache Airflow | ⭐⭐⭐ | Projects |

### ML & Analytics
| Tool | Proficiency |
|---|---|
| Python (pandas, numpy) | ⭐⭐⭐⭐⭐ |
| Scikit-learn | ⭐⭐⭐⭐ |
| Holt-Winters / ARIMA | ⭐⭐⭐⭐ |
| Statistical Modeling | ⭐⭐⭐⭐ |

### Full Stack
| Tool | Proficiency |
|---|---|
| FastAPI | ⭐⭐⭐⭐ |
| React / TypeScript | ⭐⭐⭐ |
| Java / C# / .NET | ⭐⭐⭐ |
| Docker | ⭐⭐⭐ |

---

## 📊 Featured: DemandIQ — Holt-Winters Forecast

### What it does
End-to-end demand forecasting for automotive parts using:
- **Holt-Winters Triple Exponential Smoothing** (multiplicative, auto-optimized α/β/γ via grid search)
- **Ridge Regression** with engineered lag/seasonal features
- **Gradient Boosting** ensemble
- **SQL Server** integration via FastAPI
- **Interactive dashboard** with real-time parameter controls

### Model equations
```
Level:     L_t = α·(y_t/S_{t-m}) + (1-α)·(L_{t-1}+T_{t-1})
Trend:     T_t = β·(L_t-L_{t-1}) + (1-β)·T_{t-1}
Seasonal:  S_t = γ·(y_t/L_t) + (1-γ)·S_{t-m}
Forecast:  ŷ_{t+h} = (L_t + h·T_t) · S_{t-m+h mod m}
```

### Results
| Metric | Value |
|---|---|
| MAPE | ~7% |
| Confidence Interval | 95% |
| Forecast Horizon | Up to 24 months |
| Models in Ensemble | 3 (HW + Ridge + GBM) |

---

## 🚀 Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod

# Or connect GitHub repo at vercel.com for auto-deploy on push
```

---

## 🔒 Environment Variables

```bash
# demand-forecast-holt-winters/api/.env
DB_SERVER=localhost
DB_PORT=1433
DB_NAME=demandiq
DB_USER=sa
DB_PASSWORD=your_password
DB_DRIVER=ODBC Driver 17 for SQL Server
DB_TRUST_CERT=yes
```

---

## 📬 Contact

| Channel | Link |
|---|---|
| Email | thaiskarolinebentosilva@hotmail.com |
| LinkedIn | [linkedin.com/in/thaiskaroline](https://linkedin.com/in/thaiskaroline) |
| GitHub | [github.com/thaiskaroline](https://github.com/thaiskaroline) |
| Instagram | [@thaiiskaroline_](https://instagram.com/thaiiskaroline_) |
| Location | Sorocaba, SP · Brazil (Remote · EOR eligible) |

---

## 📄 License

MIT — feel free to use as inspiration. Attribution appreciated.

---

*Built by Thais Karoline Monteiro · Data Engineer · 2026*
