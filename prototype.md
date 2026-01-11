<img width="1024" height="1024" alt="Gemini_Generated_Image_rbc7r9rbc7r9rbc7" src="https://github.com/user-attachments/assets/225c780c-d76a-49e5-aafd-950a4357ae40" />
# This diagram illustrates the end-to-end lifecycle of a grievance within our system:

- Input Layer: The system accepts unstructured text directly from the user.
- Preprocessing: We perform text cleaning and tokenization to ensure the AI receives high-quality data.
- The AI Brain (NLP): A BERT/ML Classifier handles three tasks simultaneously:
- Classification: Categorizes the issue (e.g., Police, Roads, Electricity) to ensure it reaches the right department.
- Sentiment/Urgency: Analyzes the tone and severity of the text.
- Priority Assignment: Automatically flags the complaint as High, Medium, or Low priority based on urgency scores.
- Data Persistence: All analyzed data is stored in the database for administrative action.
- User Interface: A chatbot serves as the final touchpoint, providing the user with real-time status updates.
