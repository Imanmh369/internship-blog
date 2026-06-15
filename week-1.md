# My First Week as an Intern

Starting my internship was both exciting and overwhelming.  

## Sunday – Getting Started
On the very first day, I was asked to complete administrative paperwork at **Qatar Museum Tower 1**. There, I signed my internship contract before heading to *Mathaf Museum* where my office is located. That’s where I met my supervisor, was introduced to the staff, received my access card, and got a full tour of the workplace.

## Monday – Museum Visit
My colleague Jilian and I were asked to visit the **Qatar National Museum**. We were given a tour of the museum and then tasked with observing how visitors interacted with the multimedia content. I even interviewed one visitor to get firsthand insights. Later that same day, we received a raw dataset on multimedia engagement. Our supervisor asked us to analyze and visualize it — the real start of our project.

## Tuesday – Data Cleaning
I was deep into the dataset. The first thing I noticed was that the columns needed cleaning. I began handling the data by identifying categorical and numerical variables. Using libraries like **pandas**, I cleaned, transformed, and analyzed the dataset. Missing values were filled — “No response” for categorical data, and mean or median for numerical data depending on skewness. It was my first real taste of data wrangling in a professional setting, and it felt rewarding to see the dataset take shape.

## Wednesday – CAI programme session Workshop
I attended a three‑hour workshop on **CAI**. The session explored how art and AI can intersect, sparking creativity across disciplines. We did short brainstorming exercises, generating new ideas every few minutes. At first, I struggled to grasp the concept, but as the discussion unfolded, I began to understand the potential of blending science and art. It was a challenging but eye‑opening experience.

## Thursday – NLP and Comparative Analysis
I tackled one of the harder tasks: analyzing open‑ended questions about multimedia content. Initially, I tried using **spaCy** for keyword extraction, but the results weren’t what I expected. Switching to **BERTopic** gave me much better outcomes, allowing me to extract meaningful themes. From there, I grouped different multimedia content types and carried out comparative analyses with various visitor variables. This helped me see how factors like prior knowledge or age influenced engagement with multimedia experiences.

---

## Reflections
Looking back, my first week was packed with learning. From signing contracts and meeting my team to exploring the museum, cleaning complex datasets, and experimenting with advanced NLP tools, every day brought something new. I realized that multimedia content is not just entertainment — it’s a powerful way to engage visitors, especially those with little prior knowledge.  

This week taught me that internships aren’t just about applying skills; they’re about growing, adapting, and discovering how theory meets practice. And if the first week was this full of insights, I can’t wait to see what the rest of the internship holds.

## Data Analysis
Most preferred vs Least preferred Multimedia Content

-Comparing which multimedia types visitors mentioned most positively vs least positively in open ended responses.Using difference bar charts to highlight gains/losses in preference.

<img width="702" height="423" alt="image" src="https://github.com/user-attachments/assets/6112200f-7123-4f19-adbd-0f497a165e0b" />

Prior Knowledge vs Emotional Outcomes

-	Comparing emotional responses (felt inspired, enjoyed visit, learned about culture) between knowledge groups.	Used grouped bar charts to visualize percentages of “strongly agree.”
  
<img width="717" height="426" alt="image" src="https://github.com/user-attachments/assets/e617be0a-e2f5-4766-b49b-9b7b0d523314" />

Using scipy.stats.chi2_contingency to test relationships between categorical variables where the test shows that there is no significant association. This suggest that prior knowledge did not influence whether visitor felt inspired by the museum.
<img width="813" height="239" alt="image" src="https://github.com/user-attachments/assets/a5be56e9-cc05-4cdf-9703-688ec371fe4f" />

## Extracting Keywords Using BERTopic

- Here BERTopic was able to find three main theme in Favourite multimedia content.
<img width="1057" height="602" alt="image" src="https://github.com/user-attachments/assets/f442b6ec-d267-4a00-bb50-3334e5d28f5f" />


## Suggestion for Multimedia Survey
- Make key variables (e.g., age range, nationality, prior museum knowledge, time spent) mandatory to reduce missing values and ensure complete datasets.
- Add one or two open‑ended questions to capture qualitative insights while keeping the survey concise.
- Collect demographic information early (age range, nationality, prior knowledge) to enable stronger segmentation and cross‑analysis.









