# Honolulu Tuna

### **Research Question**
- What does this data tell us about who is catching the most fish and from which country?
- What does it reveal about fishing gear types?
- Any additional insights from the data?

---

### **Methodology**
1. **Data Extraction**  
   - Use [Tabula](https://tabula.technology/) to extract the datasets from the provided documents.
  
2. **Data Understanding**  
   - Review documentation to comprehend the meaning of each row and column in the dataset.

3. **Data Analysis**  
   - Use Python and Pandas to load, view, and process the data, extracting meaningful insights and performing calculations.

---

### **Documentation**
The dataset is divided into several components. Below are descriptions of each:

#### 1. **[Estimates of Annual Catches](https://www.wcpfc.int/doc/annual-catch-estimates)**
- This includes the estimated total catch for each year across various regions.

#### 2. **[Operational Level Catch and Effort Data](https://www.wcpfc.int/doc/operational-catch-and-effort-data)**
- Provides detailed records of fishing operations, such as sets by longliners and purse seiners, and daily fishing activity by pole and line vessels and trollers. This data must be submitted to the Commission in accordance with standards.

#### 3. **[Aggregated Data](https://www.wcpfc.int/doc/aggregated-catch-and-effort-data)**
- If operational data coverage is incomplete, this section includes aggregated data for catch and effort, based on time periods and geographic regions. It is adjusted to represent the total effort for areas of 5° latitude and 5° longitude.

#### 4. **[Size Composition Data](https://www.wcpfc.int/doc/size-data)**
- This section includes data about the length and/or weight composition of the catch. It provides the finest possible resolution of time and geographical location, at least quarterly and at areas of 20° longitude and 10° latitude.

---

### **Dataset Breakdown**

#### **General Information**
- **Gear**: Type of fishing gear used (e.g., "L" for longline).
- **Flag**: The country of the vessel (e.g., "AU" for Australia).
- **Year**: The year the data was recorded.
- **Region**: The regional fisheries management area (e.g., "WCPFC" for the Western and Central Pacific Fisheries Commission).

#### **[Aggregated Data]()**
- **Annual-Catch-Estimate**: Total estimated catch (in metric tons or number of fish) for each year.
- **Aggregate-Data-Area**: Spatial resolution for aggregated catch data (e.g., "5x5" refers to a 5° latitude by 5° longitude grid).
- **Aggregate-Data-Time**: Time resolution for aggregated catch data (e.g., "MON" for monthly reporting).
- **Aggregate-Data-catch-recs**: The number of recorded catch events (or trips) per month in the specified 5x5 area.

#### **Operational Data**
- **Operational-Data-catch-recs**: Total number of fishing operations (sets or trips) conducted in the entire year, across all areas.

#### **Length Data**
- **Length-Data-Area1**: The spatial resolution for the length data.
- **Length-Data-Time1**: The time resolution for the length data (e.g., "MON" for monthly).
- **Length-Data-Size-int1**: The size class interval for length data.
- **Length-Data-Samples1**: The number of fish measured for length composition in the first dataset.

---

### **Visualizations**

Here are the charts that provide insights into tuna catch and gear usage:

1. **Countries That Caught the Most Skipjack Tuna in 2023**
   - ![Skipjack Tuna Catch](https://datawrapper.dwcdn.net/sbTg9/1/)

2. **Countries That Caught the Most Bigeye Tuna in 2023**
   - ![Bigeye Tuna Catch](https://datawrapper.dwcdn.net/xXt2y/1/)

3. **Gear Used to Catch Skipjack Tuna Over the Years**
   - ![Gear for Skipjack Tuna](https://datawrapper.dwcdn.net/bk8qD/1/)

4. **Gear Used to Catch Bigeye Tuna Over the Years**
   - ![Gear for Bigeye Tuna](https://datawrapper.dwcdn.net/6wRDl/1/)
