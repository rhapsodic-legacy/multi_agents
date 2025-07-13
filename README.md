# Multi-Agent Systems: Collaborative AI Workflows 

Multi-agent systems enable specialized AI agents to collaborate on complex tasks, offering a transparent, modular alternative to opaque large language models. This repository introduces these systems through practical examples, starting with a simple content creation workflow. Designed for students and developers, it showcases how agent-based architectures simplify AI development. 
 
The repository contains multiple folders, introducing multi-agent concepts and the ease of creating a swarm of simple AIs.
 
## Folder: crew_ai_basic  
    
This folder demonstrates a basic multi-agent system using the CrewAI framework, where three agents—Content Planner, Content Writer, and Editor—collaborate to create a blog post on "Artificial Intelligence." It highlights the simplicity of agent-based systems compared to a single complex AI.
  
### Contents    
  
- **`multi_agent.ipynb`**: Google Colab notebook implementing the multi-agent system with Google's Gemini model. 
- **`walkthrough.txt`**: Documentation explaining the code and offering student guidance for experimentation.  
 
 
## Folder: crew_ai_cx_support   

This folder contains the second lesson in a series on building multi-agent systems with CrewAI, focusing on a customer support scenario. It features two agents—a Senior Support Representative and a Support Quality Assurance Specialist—working together to address a customer inquiry from Apple about enhancing Siri with AGI elements, utilizing external tools for research.
 
### Contents 

- **`multi_agent_cx_support.ipynb`**: A Google Colab notebook implementing the customer support multi-agent system using OpenAI's GPT-3.5-turbo model and tools like SerperDevTool and ScrapeWebsiteTool.
- **`walkthrough.txt`**: Detailed documentation explaining the code, setup, and agent interactions, with guidance for students to experiment and extend the system.


## Folder: crew_ai_sales_info

This folder contains the third lesson in a series on building multi-agent systems with CrewAI, focusing on a sales lead generation and nurturing scenario. It features two agents—a Sales Representative and a Lead Sales Representative—collaborating to identify high-value leads and craft personalized outreach campaigns, demonstrated with a case study on General Electric in the nuclear power sector.

### Contents

- **`multi_agent_sales_info.ipynb`**: Google Colab notebook implementing the sales-focused multi-agent system using OpenAI's GPT-3.5-turbo model, with tools like DirectoryReadTool, FileReadTool, SerperDevTool, and a custom SentimentAnalysisTool.
- **`walkthrough.txt`**: Documentation explaining the code and providing student guidance for customizing and extending the system.




## Purpose 

- Introduce multi-agent collaboration
- Show ease of creating specialized agents
- Encourage customization and learning
- Highlight workflow transparency

## Contributing

Submit pull requests or issues to improve examples or documentation.

## License

MIT License (see LICENSE file).

---

**Start with `crew_ai_basic` to explore collaborative AI!**
