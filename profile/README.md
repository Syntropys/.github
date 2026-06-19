# 🎯 Our Capstone Project

  ![Team](https://img.shields.io/badge/Team-PJK--GM030-1F2937?style=flat-square)
  ![Program](https://img.shields.io/badge/Program-Pijak%20x%20IBM%20SkillsBuild%20(Dicoding)-1F2937?style=flat-square)
  ![Batch](https://img.shields.io/badge/Batch-1-1F2937?style=flat-square)
  ![Track](https://img.shields.io/badge/Learning%20Path-AI%20Engineer-1F2937?style=flat-square)
  ![Purpose](https://img.shields.io/badge/Purpose-Capstone%20Project-1F2937?style=flat-square)
  ![Domain](https://img.shields.io/badge/Domain-Business%20Intelligence-1F2937?style=flat-square)
  ![Phase](https://img.shields.io/badge/Phase-Final%20Release-1F2937?style=flat-square)
  ![Status](https://img.shields.io/badge/Status-Completed-1F2937?style=flat-square)
  ![Created](https://img.shields.io/badge/Created-11--Apr--2026-1F2937?style=flat-square)
  [![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-1F2937?style=flat-square)](https://github.com/Syntropys/web-frontend/blob/main/LICENSE)
  [![Maintained By](https://img.shields.io/badge/Maintained%20By-@Zevhys-1F2937?style=flat-square)](https://www.linkedin.com/in/rakha-djauhari/)
  <img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FSyntropys&countColor=%231F2937&style=flat-square&labelStyle=none" width="0" height="0">

A dual-engine Agricultural Intelligence Platform designed to forecast rice productivity across five provinces in Kalimantan and detect crop diseases. The system combines climate data from NASA POWER and agricultural statistics from BPS (Badan Pusat Statistik) for forecasting, alongside image datasets sourced from Kaggle for deep learning-based plant health diagnostics.

* **The problem:** Rice farming in Kalimantan faces two major threats: high sensitivity to climate variability and the devastating impact of crop diseases. Planners often rely on lagging historical statistics, making proactive strategy difficult, while farmers lack accessible tools for early disease identification.
* **Our approach:** We implemented a dual-model architecture. For forecasting, we developed a multivariate LSTM model as our primary predictor, benchmarked against Linear Regression, Random Forest, and XGBoost. For disease detection, we utilize a Convolutional Neural Network (CNN) trained on Kaggle datasets to accurately classify leaf imagery. Both models are served through a FastAPI backend and seamlessly integrated into an interactive React/Vite web dashboard.
* **Who it's for:** Agricultural planners, local government stakeholders, and researchers who need actionable productivity forecasts, as well as field agronomists and farmers requiring quick, data-driven plant health diagnostics.

# 👥 Meet the Team

<table>
  <tr>
    <td><b>No</b></td>
    <td><b>ID</b></td>
    <td><b>Member</b></td>
    <td><b>Role</b></td>
    <td><b>Connect</b></td>
  </tr>
  <tr>
    <td>1</td>
    <td>APC524D6Y0192</td>
    <td>Muhammad Rahman</td>
    <td>Machine Learning Deployment</td>
    <td>
      <a href="https://www.linkedin.com/in/muhammad-rahman-0874a229a/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NTIgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODU0IDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTZWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3MS0xLjg1IDMuNiAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+" height="18"/></a>
    </td>
  </tr>
  <tr>
    <td>2</td>
    <td>APC747D6X0300</td>
    <td>Siti Fitria Putri Hans</td>
    <td>AI Engineer</td>
    <td>
      <a href="https://www.linkedin.com/in/fayaesph/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NTIgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODU0IDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTZWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3MS0xLjg1IDMuNiAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+" height="18"/></a>
    </td>
  </tr>
  <tr>
    <td>3</td>
    <td>APC216D6Y0441</td>
    <td>Muhammad Rakha Djauhari</td>
    <td>Project & Quality Assurance</td>
    <td>
      <a href="https://www.linkedin.com/in/rakha-djauhari/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NTIgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODU0IDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTZWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3MS0xLjg1IDMuNiAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+" height="18"/></a>
    </td>
  </tr>
  <tr>
    <td>4</td>
    <td>APC480D6Y0457</td>
    <td>M. Rohid Rivaldi</td>
    <td>Front-end AI Integration</td>
    <td>
      <a href="https://www.linkedin.com/in/rohidrivaldi/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NTIgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODU0IDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTZWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3MS0xLjg1IDMuNiAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+" height="18"/></a>
    </td>
  </tr>
  <tr>
    <td>5</td>
    <td>APC524D6Y0481</td>
    <td>Muhammad Husain Ali Ridha</td>
    <td>AI Engineer</td>
    <td>
      <a href="https://www.linkedin.com/in/muhammad-husain-ali-ridha/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NTIgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODU0IDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTZWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3MS0xLjg1IDMuNiAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+" height="18"/></a>
    </td>
  </tr>
</table>

# 🙏 Acknowledgments

Special thanks to the parties that supported our capstone journey:

- **Pijak Program** — Independent study framework & program structure
- **IBM SkillsBuild** — AI Engineer curriculum & learning resources
- **Dicoding** — Program operations & learning platform
- **Our Facilitators** — Guidance during ILT sessions and continuous mentoring
- **Our Mentor Advisors** — Project insights, direction, and constructive feedback
- **Our Academic Advisors** — Administrative support from our respective universities

# 📜 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPLv3)** — see the [LICENSE](./LICENSE) file for full details.

# ⚠️ Disclaimer

While we welcome open collaboration through forks and pull requests—**and encourage you to reach out if you plan to build something significant upon this project**—please note that our model predictions are strictly experimental and must not serve as the sole basis for real-world agricultural or policy decisions.
