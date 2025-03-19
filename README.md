## 🎯 AI Lead Generation Agent - Powered by Firecrawl's Extract Endpoint

The AI Lead Generation Agent automates the process of finding and qualifying potential leads from Quora. It uses Firecrawl's search and the new Extract endpoint to identify relevant user profiles, extract valuable information, and organize it into a structured format in Google Sheets. This agent helps sales and marketing teams efficiently build targeted lead lists while saving hours of manual research.

### Features
- **Targeted Search**: Uses Firecrawl's search endpoint to find relevant Quora URLs based on your search criteria
- **Intelligent Extraction**: Leverages Firecrawl's new Extract endpoint to pull user information from Quora profiles
- **Automated Processing**: Formats extracted user information into a clean, structured format
- **Google Sheets Integration**: Automatically creates and populates Google Sheets with lead information
- **Customizable Criteria**: Allows you to define specific search parameters to find your ideal leads for your niche

### How to Get Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ShreySigh2912/Leadgenerator.git
   cd Leadgenerator
   ```

2. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Google Sheets Integration**:
   - In your terminal, run: `composio add googlesheets`
   - In your Composio dashboard, create a new Google Sheet integration
   - Make sure it is active in the active integrations/connections tab

4. **Set up your API keys**:
   - Get your Firecrawl API key from [Firecrawl's website](https://www.firecrawl.dev/app/api-keys)
   - Get your Composio API key from [Composio's website](https://composio.ai)
   - Get your OpenAI API key from [OpenAI's website](https://platform.openai.com/api-keys)

5. **Run the application**:
   ```bash
   streamlit run ai_lead_generation_agent.py
   ```

### Usage

1. Open the application in your browser (default: http://localhost:8501)
2. Enter your API keys in the sidebar
3. Set the number of links you want to search (default: 3, max: 10)
4. Enter your lead generation query in the text area
5. Click "Generate Leads"

### Example Queries
- "Looking for users who need automated video editing software with AI capabilities"
- "Generate leads looking for AI-powered customer support chatbots for e-commerce stores"
- "Find people interested in voice cloning technology for creating audiobooks and podcasts"

### Output
The application will:
1. Transform your query into a focused search term
2. Search for relevant Quora URLs
3. Extract user information from those URLs
4. Create a Google Sheet with the lead information
5. Provide you with a link to the generated sheet

### Requirements
- Python 3.8+
- Streamlit
- Firecrawl API
- OpenAI API
- Composio API
- Google Sheets API (via Composio)

### License
MIT License

### Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

