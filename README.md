# CheMin Interactive Viewer

This is a Python Dash application for interactive visualization of mineral abundance data collected by the **CheMin instrument** aboard the **Curiosity Rover** on Mars.

It allows users to:
- Select a specific **sol** (Martian day)
- Visualize mineral abundance data with error bars
- See the corresponding location on a Mars map

## 🔧 Features

- Interactive plot of mineral abundance (%)
- Tooltips and popups showing elevation and coordinates
- Leaflet-based Mars basemap
- Ready for new data input from CheMin

## 📁 Folder Structure

```
CheMin-Interactive-Viewer/
├── data/
│   ├── combined_chemin_data_all_sols.csv
│   └── combined_sol_data.csv
├── CheMin_Interactive_Viewer.ipynb
├── paper.md
├── LICENSE
├── .gitignore
└── README.md
```

## ▶️ How to Run

Install the required packages:

```bash
pip install dash dash-leaflet plotly pandas
```

Then run the app:

```bash
jupyter notebook CheMin_Interactive_Viewer.ipynb
```

## 📊 Data

You must place two CSV files in the `data/` folder:
- `combined_chemin_data_all_sols.csv`
- `combined_sol_data.csv`

If you want to use your own data, follow the same structure and format as shown in the provided files.

## 📜 License

This project is licensed under the [MIT License](LICENSE).
