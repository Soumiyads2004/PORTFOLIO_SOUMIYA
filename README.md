 ### Spotify Analysis Dashboard
### Problem Statement:
This dashboard offers insights into popular songs, artists, and streaming patterns on Spotify. It allows Spotify to understand the performance of various tracks and artists based on key metrics such as danceability, liveness, and total streams. The objective is to help Spotify identify popular trends and artist performances, which can guide decision-making for playlist curations, artist promotions, and enhancing user experiences.

### Steps Followed:
- **Step 1:** Load the Spotify dataset into Power BI Desktop. The dataset contains key features of tracks such as "Danceability," "Liveness," "Streams," "Artist Name," and more.
- **Step 2:** In Power Query Editor, use "Column Distribution," "Column Quality," and "Column Profiling" to understand the data.
- **Step 3:** The dataset had no errors or empty values in most columns except for "Liveness." Null values in the "Liveness" column were ignored for percentage calculations since they accounted for less than 1% of the data.
- **Step 4:** Use the report view to add visualizations like bar charts and line charts that show streaming patterns by artist and time period.
- **Step 5:** Add slicers for filters such as "Track Mode," "Key," and "Track Name" to make the data more interactive for users.
- **Step 6:** Add card visuals to display key metrics like total streams, average danceability, and the sum of liveness percentages.
- **Step 7:** Create calculated columns using DAX to group artists and analyze performance based on age groups or regions, depending on data availability.
- **Step 8:** The report was published on Power BI Service for sharing and collaboration.

Insights:
1. **Total Streams:** The total number of streams across all tracks and artists is approximately 37.87 billion, with November being the peak month with over 8.7 billion streams.
2. **Popular Tracks:** Songs like *Blinding Lights* by The Weeknd, *Watermelon Sugar* by Harry Styles, and *Circles* by Post Malone rank among the most-streamed tracks.
3. **Top Artists:** Artists like Taylor Swift, Dua Lipa, and Harry Styles consistently dominate in terms of danceability and liveness metrics, which indicates high engagement from listeners.
4. **Average Metrics:**
   - **Danceability:** Some artists like Tones and I, and Maroon 5 have higher danceability scores, showing that their songs are more suited for dance-related activities.
   - **Liveness:** Artists such as Labrinth and Chris Brown have higher liveness scores, reflecting more live music elements in their tracks.
5. **Streaming Trends:** The dashboard shows a spike in streaming during November and May, which could align with holiday seasons or major music releases.
  
This dashboard allows Spotify to track performance metrics effectively and make data-driven decisions to cater to audience preferences.

For cleaning of the data I have removed all the null values,errors, etc.
![cleaning in power query](https://github.com/user-attachments/assets/77835359-e341-49e6-96e6-8fe16d43862d)

The Dashboard looks like this-
![ACTUAL DASH](https://github.com/user-attachments/assets/ca2e9790-68cf-489f-8f70-5ac40408dc39)

When you click on a certain song the deatials of the song can be viewed in the dashboard-
![CRUEL_ANALYSIS](https://github.com/user-attachments/assets/3a5e10e9-77df-4e48-beee-136b1c912896)
