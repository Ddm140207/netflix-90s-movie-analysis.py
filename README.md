# netflix_90s_movie_analysis.py

🎬 **Netflix 90s Movie Analysis**  
A data-driven exploration of movie trends on Netflix, focusing on 1990s releases.  
This project analyzes patterns in movie durations — particularly short action films from that decade — using Python, Pandas, and Matplotlib for data visualization.

---

**Netflix**, founded in 1997 as a DVD rental service, has grown into one of the world's largest entertainment platforms.

With its extensive library of movies and series, Netflix provides a great opportunity to apply data science techniques and uncover meaningful insights from its content catalog.


## The data
### **netflix_data.csv**
| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

---

## 🔍 Key Discoveries

### ❓ What was the most common movie duration in the 1990s?
The most ***frequent movie duration for 1990s*** titles in the Netflix dataset is **94 minutes**.  
This slightly surpasses the industry’s typical average of 90 minutes, suggesting that Netflix’s 90s catalog may lean toward slightly longer films.


### 🎬 How many short movies were released in the 1990s? (Less than 90 mins)
A total of **184 short action movies** from the 1990s are present in the dataset.
