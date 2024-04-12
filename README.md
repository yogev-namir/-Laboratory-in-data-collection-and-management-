# Career Advancement Tool (CAT) <!-- Largest title: h1 -->
  BECAUSE OF A PROBLEM WITH VIEWING THE NOTEBOOK IN A NORMAL FORMAT, WE ARE KINDLY ASKING YOU TO DONWLOAD THE HTML OR IPYNB FILE IN ORDER TO VIEW OUR WORK.
## Introduction <!-- Second largest title: h2 -->
CAT is an innovative feature within LinkedIn, designed to increase job marketability by aligning user resumes with current industry standards and suggesting skill enhancements through Machine Learning and Large Language Models (LLM). The tool focuses on bridging the gap between current professional skills and the ever-evolving job market requirements.

### Data Collection and Integration <!-- h3 -->
Data sources include LinkedIn's profile dataset complemented by web scraping for real-time job market demands and LinkedIn Learning courses. We strategically focus on the data science sector, integrating a neural network to predict relevant skills, which achieved over 90% accuracy on our datasets.
Top frequent skill count in the kaggle job postings dataset:
![image](https://github.com/yogev-namir/Linkedin-Career-Advancement-Tool-CAT/assets/81235287/93d66362-50cb-43fe-849a-1a3c72eae86f)


### AI Methodologies <!-- h4 -->
The project leverages several AI techniques:

DistilBert for tokenizing job titles into vectors.
Neural Network for predicting skills from job titles and company names.
Bucketed Random Projection LSH and KNN for matching user profiles to job opportunities.
Gemini LLM for extracting skills, generating insights, and recommending courses, with an adjusted selection of 750 courses to fit token limits.
### Evaluation and Results <!-- h5 -->
The neural network shows strong predictive performance. The combination of BRP LSH and KNN provides precise profile matching. Gemini's recommendations have led to positive user engagement and profile improvements.

### Limitations and Reflections <!-- Smallest title: h6 -->
Challenges such as unavailable skills data, initial KNN implementation hurdles, and computational performance were addressed through innovative solutions, including a neural network for skill prediction and a refined two-step matching process.

## Conclusion <!-- Back to h2 for section consistency -->
CAT has demonstrated the potential to enhance career development significantly. Despite limitations, the tool has successfully provided personalized guidance and recommendations, establishing itself as a valuable asset in the job-seeking process.
