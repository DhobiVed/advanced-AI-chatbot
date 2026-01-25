# Advanced AI Chatbot Suite

## 📸 Application Screenshots

### Home Interface
![Home Page](Screenshot%202025-07-20%20165126.png)
*Main dashboard with chatbot selectin*

![PDF Q&A Screenshot](Screenshot%202025-07-20%20165018%20-%20Copy%20-%20Copy.png)

### Search Chatbot Interface  
![Search Interface](Screenshot%202025-07-20%20165411.png)
*Search chatbot with model selection options*

![Search Query](Screenshot%202025-07-20%20165505.png)
*Example search query and AI response*

![History Sidebar](Screenshot%202025-07-20%20165612.png)
*Conversation history panel*

### PDF Chatbot Interface
![PDF Upload](Screenshot%202025-07-20%20165648.png)
*PDF document upload interface*

![Document Processing](Screenshot%202025-07-20%20165843.png)
*PDF text extraction in progress*

![Processed PDF](Screenshot%202025-07-20%20170114.png)
*Successfully processed PDF with statistics*

![Q&A Section](Screenshot%202025-07-20%20170140.png)
*Question answering interface for PDF content*

![Answer Display](Screenshot%202025-07-20%20170236.png)
*Detailed answer with confidence score*

![Summary Generation](Screenshot%202025-07-20%20170504.png)
*Document summarization options*

![Generated Summary](Screenshot%202025-07-20%20170525.png)
*AI-generated document summary*

### Advanced Features
![Document Statistics](Screenshot%202025-07-20%20170831%20-%20Copy.png)
*Detailed document analytics and metrics*

![Search Results](Screenshot%202025-07-20%20170857.png)
*Semantic search results from PDF content*

![Context View](Screenshot%202025-07-20%20170938.png)
*Relevant context extraction from document*

![Alternative Answers](Screenshot%202025-07-20%20170957.png)
*Multiple answer suggestions with scores*

### UI Details
![Model Settings](Screenshot%202025-07-20%20171024.png)
*Advanced model configuration options*

![Processing Status](Screenshot%202025-07-20%20171116.png)
*Real-time processing indicators*

![Error Handling](Screenshot%202025-07-20%20171147.png)
*Error messages and recovery options*

![Response Formatting](Screenshot%202025-07-20%20171223.png)
*Beautifully formatted AI responses*

![Navigation](Screenshot%202025-07-20%20171404.png)
*Sidebar navigation and settings*

![Final Results](Screenshot%202025-07-20%20171432.png)
*Completed analysis with export options*

## 🚀 Quick Setup

### Step 1: Rename your screenshots
Run this Python script to rename all screenshots:

```python
import os

# Create screenshots folder if it doesn't exist
os.makedirs('screenshots', exist_ok=True)

# List of all your screenshot files (replace with your actual filenames)
screenshots = [
    "Screenshot 2025-07-20 165126.png",
    "Screenshot 2025-07-20 165411.png", 
    "Screenshot 2025-07-20 165505.png",
    "Screenshot 2025-07-20 165612.png",
    "Screenshot 2025-07-20 165648.png",
    "Screenshot 2025-07-20 165843.png",
    "Screenshot 2025-07-20 170114.png",
    "Screenshot 2025-07-20 170140.png",
    "Screenshot 2025-07-20 170236.png",
    "Screenshot 2025-07-20 170504.png",
    "Screenshot 2025-07-20 170525.png",
    "Screenshot 2025-07-20 170831 - Copy.png",
    "Screenshot 2025-07-20 170857.png",
    "Screenshot 2025-07-20 170938.png",
    "Screenshot 2025-07-20 170957.png",
    "Screenshot 2025-07-20 171024.png",
    "Screenshot 2025-07-20 171116.png",
    "Screenshot 2025-07-20 171147.png",
    "Screenshot 2025-07-20 171223.png",
    "Screenshot 2025-07-20 171404.png",
    "Screenshot 2025-07-20 171432.png"
]

# Move and rename files (if they exist)
for old_name in screenshots:
    if os.path.exists(old_name):
        # Replace spaces with %20 for URLs
        new_name = old_name.replace(" ", "%20")
        os.rename(old_name, f"screenshots/{old_name}")
        print(f"Moved: {old_name}")
    else:
        print(f"Not found: {old_name}")
