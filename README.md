# Multi-Agent Systems: Collaborative AI Workflows 

Multi-agent systems enable specialized AI agents to collaborate on complex tasks, offering a transparent, modular alternative to opaque large language models. This repository introduces these systems through practical examples, starting with a simple content creation workflow. Designed for students and developers, it showcases how agent-based architectures simplify AI development. 

The repository contains multiple folders, with `crew_ai_basic` as the first, introducing multi-agent concepts and the ease of creating a swarm of simple AIs.

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


### Purpose 

- Introduce multi-agent collaboration
- Show ease of creating specialized agents
- Encourage customization and learning
- Highlight workflow transparency

## Getting Started

1. Open `multi_agent.ipynb` in Google Colab
2. Replace `"YOUR_KEY_HERE"` with your Gemini/ OpenAI API key
3. Run the notebook
4. Refer to `walkthrough.txt` for code details and experiment ideas

## Future Folders

Additional folders will explore advanced multi-agent systems, building on `crew_ai_basic`.

## Contributing

Submit pull requests or issues to improve examples or documentation.

## License

MIT License (see LICENSE file).

---

**Start with `crew_ai_basic` to explore collaborative AI!**
