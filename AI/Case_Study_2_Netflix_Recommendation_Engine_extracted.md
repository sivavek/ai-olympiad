National AI Olympiad: case study two: Netflix's recommendation engine (from part two)
=====================================================================================

**The scenario:** How does Netflix always seem to know exactly what movie or show you what want to watch next? it's not magic; it's a powerful combination of different machine learning types.

**AI concepts in action:**
- **supervised learning (chapter 4)** Netflix uses your past ratings when you give a show a "thumbs up", you are providing labeled data. The AI learns: this user likes shows with these actors, this genre and this style. It then looks for new similar shows to recommend.
  
- **unsupervised learning (chapter 4):** what about finding new types of shows you might like? the AI uses unsupervised learning to analyze the view viewing habits of millions of users. it might discover hidden clusters or patterns such as people who watch cooking shows on Tuesdays also tend to watch historical documentaries. This helps Netflix create new recommendation categories, like "quirky comedies", or "gritty sci-fi".
  
- **reinforcement learning (chapter 4):** the entire recommendation system is a form of reinforcement learning. when you click on and watch a recommended show, you give the AI a **reward**. This tells the AI, "that was a good suggestion". If you ignore recommendation the AI learns that it wasn't a good fit, and will be less likely to suggest something similar in the future.

**The result:** By combining these ML techniques, Netflix creates a personalized experience that keeps you engaged and helps you discover new content you'll love.
