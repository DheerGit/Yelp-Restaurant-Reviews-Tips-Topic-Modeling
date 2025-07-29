# 🗣️ Yelp Data Analysis: Unstructured Data

**CIS 509 – Analytical Unstructured Data** | Mar 2025  
**Team 011:** Ayush Trivedi, Dheeraj Pamnani, Dominic Darrah, Riya Agarwal, Sravani Bolla   

---

## 🚀 Business Problem  
Restaurants’ customer satisfaction hinges on food quality, service, pricing, and ambiance. By mining Yelp reviews, tips and star‐ratings, we identify themes driving positive or negative experiences—enabling data‐driven improvements. 

---

## 📊 Data & Scope  
- **Source:** Yelp Open Dataset (Business, Review, Tip)   
- **Filters:**  
  - **States:** Florida (FL), Pennsylvania (PA)  
  - **Cuisines:** American, Chinese, Italian  
- **Processed CSVs:**  
  - `F_filtered_business.csv`  
  - `F_filtered_review.csv`  
  - `F_filtered_tip.csv`  
  - `F_filtered_user.csv`   

---

## 🔬 Methodology  
1. **Exploratory Data Analysis (EDA):**  
   - Star‐rating distribution, review lengths, common bigrams/trigrams (e.g., “food good”, “highly recommend”)   
2. **Sentiment Analysis:**  
   - Classify reviews by star rating; extract themes in 1-star (service complaints, delays) vs. 5-star (food quality, service praise)   
3. **Topic Modeling:**  
   - Clean tip text, apply BERTopic + UMAP → 30 topics via HDBSCAN; visualize topic prevalence by cuisine & state   
4. **Regional & Cuisine Comparison:**  
   - Compare topic frequencies across FL vs. PA and American/Chinese/Italian segments  

---

## ✨ Key Findings  
- **Sentiment Themes:**  
  - **1-Star:** Service issues, wait times, food complaints  
  - **5-Star:** Food quality, great service, ambiance   
- **Topic Insights:**  
  - *Food Quality & Service* dominate positive feedback  
  - *Reservations & Parking* are key neutral topics  
  - *Tipping Issues* and *Service Complaints* drive negative reviews  
- **Cuisine Variations:**  
  - **American:** Wings, brunch, happy-hour specials  
  - **Italian:** Pizza, pasta, wine pairings, gluten-free options  
  - **Chinese:** Authentic Sichuan dishes, occasional service complaints   
- **Regional Differences:**  
  - **Florida:** Outdoor seating, brunch focus, higher Italian & seafood mentions  
  - **Pennsylvania:** Parking & tipping concerns, higher wings & pancakes mentions  

---

## 📝 Recommendations  
- **Elevate Signature Dishes:** Spotlight popular brunch and happy-hour menus  
- **Streamline Service:** Improve reservation workflows and queue management  
- **Enhance Ambiance:** Expand outdoor seating in FL; address parking in PA  
- **Clarify Tipping:** Standardize gratuity policies and customer communication  

---

## 📂 Repository Structure  
