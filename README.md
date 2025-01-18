# Students_Recommendations
Project Overview
This project analyzes quiz performance data to provide students with personalized recommendations for improving their preparation. The solution utilizes data from current and historical quizzes to identify performance trends, weak areas, and strengths, generating actionable insights to guide students toward better learning outcomes.

Features
• Data Analysis: Identifies patterns in quiz performance based on topics, difficulty levels, and response accuracy.
• Insights Generation: Highlights weak areas, strengths, and improvement trends.
• Recommendations: Provides personalized recommendations with creative labels and actionable steps.
• Student Personas: Groups students into clusters based on performance metrics using k-means clustering.
• Visualizations: Includes bar charts, line plots, and scatterplots for clear insights.

Setup Instructions
1) Clone the repository:   git clone <repository-link>
2) Navigate to the project directory:   cd project-name
3) Install dependencies: pip install -r requirements.txt
4) Run the script: python main_script.py

Data Sources
Current Quiz Data: https://www.jsonkeeper.com/b/LLQT ,  https://api.jsonserve.com/rJvd7g 
Historical Quiz Data: https://api.jsonserve.com/XgAgFJ

Approach
1) Data Fetching:
   • Retrieved data from provided API endpoints.
2) Data Analysis:
   • Calculated average scores, weak areas, and accuracy trends.
   • Analyzed quiz performance by topics and difficulty levels.
3) Insights Generation:
   • Identified strengths and weaknesses with creative labels.
   • Generated actionable recommendations for improvement.
4) Student Persona Clustering:
   • Used k-means clustering to group students into personas based on performance metrics.
5) Visualizations:
   • Created charts to represent weak areas, score trends, and student personas

Recommendations
Examples of generated recommendations:
   • Struggler in Topic 20: Focus on foundational concepts and practice targeted questions. Use videos and mock tests for support.
   • Performer in Topic 51: Continue excelling by practising advanced-level questions.

Bonus Features
   • Student Personas: Categorized students into distinct groups for tailored support.
   • Creative Insights: Provided strengths and weaknesses with engaging labels.
