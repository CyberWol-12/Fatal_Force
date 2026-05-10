#  US Police Fatalities: Data Science Case Study 

##  Project Overview
Is project mein maine **US Police Shootings** ke sensitive aur complex dataset ka end-to-end analysis kiya hai. Maine do alag datasets (Fatalities Data aur US Census Data) ko merge karke social, economic, aur demographic factors ke beech ka correlation dhoonda hai.



## Tech Stack & Skills
* **Language:** Python
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`, `Plotly Express` (Interactive)
* **Time-Series:** Resampling, Downsampling
* **Geospatial:** Choropleth Mapping



## 🚀 Key Insights & Visualizations

### 1. Demographic Analysis (Race & Gender)
Total numbers ke muqable jab humne population share dekha, toh minorities par disproportionate impact nazar aaya.
* **Image 1:** ![Race Distribution](link_to_your_image)
* **Image 2:** ![Gender Analysis](link_to_your_image)

### 2. Socio-Economic Correlation (Poverty vs Education)
Maine `Twin Axes` chart ka use karke proof kiya ki poverty rate aur high school graduation ke beech inverse relation hai, jo in incidents ke areas ko identify karne mein madad karta hai.
* **Image 3:** ![Poverty vs Education Chart](link_to_your_image)

### 3. Geographical Mapping
Plotly Choropleth map ke zariye humne US ke states ko "Fatalities Intensity" ke hisaab se visualize kiya.
* **Image 4:** ![US States Choropleth Map](link_to_your_image)

### 4. Time-Series Trend Analysis
Daily data ko monthly trends mein convert karne ke liye maine **Resampling (Downsampling)** ka use kiya taaki long-term patterns samajh aa sakein.
* **Image 5:** ![Interactive Monthly Trend](link_to_your_image)

---

## 🧹 Data Cleaning Challenges
* **City Name Normalization:** Census data mein shehron ke naam ke aage "city", "town", aur "CDP" suffix tha, jise regex se clean kiya taaki accurate merging ho sake.
* **Date Conversion:** `Object` types ko `datetime64[ns]` mein badla taaki time-series analysis possible ho.
* **Handling Nulls:** Age aur Race columns mein missing data ko intelligently handle kiya.

---

## 🧠 Conclusion
* **Consistency:** Trend line batati hai ki incidents ka rate 2015-2017 ke beech lagbhag sthir (consistent) raha.
* **Mental Health:** Analysis mein paya gaya ki lagbhag **25%** cases mein victim mental illness se jujh raha tha.
* **Evidence-Based Learning:** Yeh project dikhata hai ki kaise data social awareness aur policy-making mein bada role play kar sakta hai.

---

## 📂 How to Use
1. Clone this repository.
2. Install requirements: `pip install pandas seaborn plotly`.
3. Open `Police_Analysis.ipynb` in Jupyter Notebook.

---
**Developed with ❤️ by Divya**