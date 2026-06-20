# OW-AHBM
# Overwatch Workshop: • ANY HERO BOSS MODE •

An ongoing, 8-year passion project for a custom Overwatch game mode. This project originally began as a hobby during my university years and has evolved into a massive, feature-rich script.

## ⚠️ Project Status: The Great Refactor
The script currently sits at **~20,000 lines of code** and is aggressively hitting the Overwatch Workshop's internal memory/script size limits. 

Because this was built progressively over nearly a decade, the codebase is heavily unorganized and contains legacy logic. **The primary goal of this GitHub repository is optimization and refactoring.**

### Current Objectives:
*   **De-duplication:** Identifying redundant rule sets and combining actions.
*   **Variable Optimization:** Consolidating global/player variables to free up space.
*   **String/Effect Management:** Slashing unnecessary HUD elements or heavy loops that trigger server load.

## 🤝 Contributing
If you are a fellow Workshop developer looking to help optimize, clean up legacy logic, or suggest modular fixes, contributions are incredibly welcome! 
* Please fork the repo and submit a Pull Request.
* Use the GitHub diff tool to highlight exactly which rules or actions you've optimized or removed.
