<!--
author: AI in TVET Workshop Team
email: 
version: 1.0.0
language: en
narrator: US English Female
comment: Interactive 90-minute workshop on AI applications in TVET education for Sri Lankan teachers
logo: https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Tensorflow_logo.svg/1915px-Tensorflow_logo.svg.png

link: link: https://raw.githubusercontent.com/OVGU-VET-TechEd/Integrating_AI_in_TVET_UNESCO/refs/heads/main/Vorlage.css

@style
.sector-card {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 2rem;
    margin: 1rem;
    border-radius: 15px;
    box-shadow: 0 8px 32px rgba(0,0,0,0.3);
    transition: transform 0.3s ease;
}

.sector-card:hover {
    transform: translateY(-5px);
}

.ai-tool-demo {
    background: #f8f9fa;
    border: 2px solid #007bff;
    border-radius: 10px;
    padding: 1.5rem;
    margin: 1rem 0;
}

.quiz-interactive {
    background: linear-gradient(45deg, #ff6b6b, #ffa726);
    color: white;
    padding: 1rem;
    border-radius: 10px;
    margin: 1rem 0;
}

.resource-link {
    background: #28a745;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    text-decoration: none;
    display: inline-block;
    margin: 0.25rem;
    transition: all 0.3s ease;
}

.resource-link:hover {
    background: #218838;
    transform: scale(1.05);
}
@end

@customQuiz
[[...]]
<script>
"@0" == btoa( "@input".trim().toLowerCase() )
</script>
@end

@aiDemo: <div class="ai-tool-demo">**AI Demo:** @0<br>**Tool:** @1<br>**Try it:** [Click here](@2)</div>

@sectorCard: <div class="sector-card">**@0**<br>@1</div>

@resourceLink: <a href="@1" class="resource-link" target="_blank">@0</a>

-->


<svg xmlns='http://www.w3.org/2000/svg' width='1100' height='400' viewBox='0 0 800 450'>
<!-- Background -->
<rect width='800' height='450' fill='#2196f3' />
<!-- White rounded rectangle container -->
<rect x='50' y='50' width='700' height='350' rx='20' fill='white' />
<!-- Main Title -->
<text x='400' y='110' font-family='Segoe UI, Arial, sans-serif' font-size='28' font-weight='bold' text-anchor='middle' fill='#2196f3'>
Open Educational Resources (OER)
</text>
<text x='400' y='140' font-family='Segoe UI, Arial, sans-serif' font-size='28' font-weight='bold' text-anchor='middle' fill='#2196f3'>
Learning Material Development
</text>
<text x='400' y='170' font-family='Segoe UI, Arial, sans-serif' font-size='24' font-weight='bold' text-anchor='middle' fill='#2196f3'>
with LiaScript and AI
</text>
<!-- Author -->
<text x='400' y='210' font-family='Segoe UI, Arial, sans-serif' font-size='16' font-weight='bold' text-anchor='middle' fill='#666'>
Hannes Tegelbeckers
</text>
<text x='400' y='230' font-family='Segoe UI, Arial, sans-serif' font-size='14' text-anchor='middle' fill='#666'>
Research Assistant, PhD Student
</text>
<!-- Institution -->
<text x='400' y='255' font-family='Segoe UI, Arial, sans-serif' font-size='13' font-weight='bold' text-anchor='middle' fill='#999'>
Professorship of Engineering Pedagogics and Technical Education
</text>
<text x='400' y='275' font-family='Segoe UI, Arial, sans-serif' font-size='13' font-weight='bold' text-anchor='middle' fill='#999'>
Otto von Guericke University Magdeburg
</text>
<!-- Event Info -->
<text x='400' y='310' font-family='Segoe UI, Arial, sans-serif' font-size='14' font-weight='bold' text-anchor='middle' fill='#2196f3'>
2nd Regional DS2S Networking Event
</text>
<text x='400' y='330' font-family='Segoe UI, Arial, sans-serif' font-size='12' text-anchor='middle' fill='#666'>
Innovate Together: Shaping Education for the digital era
</text>
<text x='400' y='350' font-family='Segoe UI, Arial, sans-serif' font-size='12' text-anchor='middle' fill='#666'>
3rd - 5th September 2025, Leipzig, Germany
</text>
<!-- Project Attribution -->
<text x='400' y='375' font-family='Segoe UI, Arial, sans-serif' font-size='11' text-anchor='middle' fill='#999'>
Digital Skills to Succeed in Asia (DS2S) Project | Commissioned by BMZ
</text>
</svg>

<!-- License info -->
<div style="position: fixed; bottom: 10px; right: 10px; font-size: 12px; opacity: 0.7;">
  <img src="media/CC_BY-SA_icon.png" alt="CC BY-SA" style="height: 20px; vertical-align: middle;">
  <a href="https://creativecommons.org/licenses/by-sa/4.0/" style="margin-left: 5px; text-decoration: none;">CC BY-SA 4.0</a>
</div>

# Cours Goal
- Outlining the context and a possible framework for the use of Ai in  Open Educational Ressources
- Update or double check you AI tool box
- Use a text based approache (Mark Down) to create teaching and learning material


## what is AI

- there is no current defintion
- currently we are talking mainly about probablitiy machines
- Nature of knowldege production - gen AI is the past (it learned from the past and mainly presents that to us)

Human factor:
- we attribute understanding or consciouse to generated text which is not there

Core question: 
- what do we want to automate

**Examples:**
- AI Excells in sepcific tasks 
 - Spotting Cancer, quality of crops, quality of welding
 - {{further examples}}

## Open Edcuational Resources

Defintion and Scope (2019)
An **Open Educational Resource (OER)** is defined in the Dubai Declaration as learning, teaching, and research materials in any format and medium that reside in the public domain or under copyright but have been released under an open license, permitting no-cost access, reuse, repurpose, adaptation, and redistribution by others. OER includes textbooks, multimedia, course materials, and other resources that prioritize inclusivity, equity, and collaboration in education, often supported by emerging technologies such as AI for better accessibility and adaptability.[^3][^4][^2][^1]

An **open license** refers to a legal tool that allows creators to maintain ownership of their work while also specifying the terms under which others may freely use, reuse, adapt, and redistribute the material. Open licenses are designed to facilitate sharing and collaboration, ensure proper attribution, and enable scalable, flexible access to educational resources. They are central to the OER ecosystem and must now be updated to clarify how content may be used—including use as training data for AI models—and how attribution and compatibility should be ensured for all derivative works created using emerging technologies.[

Lubliana Declaration
!?[UNESCO OER Lubliana Recommendation](https://)


The UNESCO 2019 Recommendation in OER (Open Education Resources)
!?[UNESCO OER Recommendation](https://)
- every 4 years governments have to decalre what they have done

Introducing the Dubai Declaration
- provide link 
!?[Dubai Declaration](https://)

> **Open Source AI System**

- Freedoms (Use, Study , Modify, Share)
- Open Weights (Model Wigths and parameters)
- Open Code (all source code, source code to tain the system, source code used to create the dataset)
- Data (The compele list of data used to train the system and the actual dataset when allowed)

!?[Open AI System Defintion](https://opensource.org/ai/open.ksource.ai-defintion)

## Orientation: UNESCO AI Framework for Teachers


| Competency | Acquire | Deepen | Create |
|------------|---------|--------|--------|
| **Human-centred Mindset** | @normalCell(Critically reflect on benefits, limitations and risks of AI tools in local educational settings) | @normalCell(Apply human-centered principles in AI tool selection) | @normalCell(Design AI-enhanced learning experiences prioritizing human agency) |
| **Ethics of AI** | @normalCell(Understand basic AI ethical principles) | @normalCell(Analyze ethical implications of AI in education) | @normalCell(Develop ethical guidelines for AI use in teaching) |
| **AI Foundations & Applications** | @normalCell(Learn basic AI concepts and educational tools) | @normalCell(Integrate AI tools into teaching practice) | @normalCell(Create innovative AI-enhanced learning solutions) |
| **AI Pedagogy** | @normalCell(Understand AI's role in pedagogy) | @normalCell(Adapt teaching methods with AI support) | @normalCell(Design AI-integrated pedagogical approaches) |
| **AI for Professional Learning** | @normalCell(Use AI for personal professional development) | @normalCell(Collaborate with AI for continuous learning) | @normalCell(Lead professional development in AI literacy) |

> Check out the framework: [UENSCO AI Framework for Teachers 2024](https://)



## Why Lias Script

- e.g. Why LiaScript - text based, easy to generate, easy to render, share and adapt (e.g. translate)
- dynamic options vs. static presentation choices


**For your consideration on text based material**

- What is you data strategy
- how does your datastrategy will influence decisions regarding platforms and systems
- how does your datastrategy will influence future integration into digital ecosystems, set ups for learning and teaching tools (Intellgient Tutorting Systems, LMS implementation, personalised learning) and industry developments regarding changing skill proficiency and competencies)

## AI Examples

> **LLM**
- [Perplexity Ai](https:)
- [Claude AI](https:)
- [Copilot](https:)
- [ChatGPT](https:)

> **Presentations and Other**
- [grammer.app](https:)
- [napking AI](https:)
- [lmnotebook](https:)


> **Local Model implementation GUI**
- [GPT4all](https:)
- [Ollama](https:)
- [LM](https:)
- [Hugging Face]

> **Local Model Implementation CLI**
- [Ollama](https:)


> **Avatar Generation**
- [HeyGen Ai](https:)

# Refresh: Prompting
- What is a prompt
- Different ways to prompt
- 

# Hands on

> **Generate your own Selflearning Tool for a specific topic**
- define your goal and learning objective
- define methods
- define interactive tools

- choose an LLM and communicate those decisions
- create a LiaSCript selflearning tool for your objective
- copy your output code into: [Liascript Live Editor](https://liascript.github.io/LiveEditor/?)

> usable prompting option: 5 step frame(by google)

- **Task:** What the AI shall do!
- **Context:** Background information and details relevant to the task.
- **References:** Any external sources or materials to consider.
- **Evaluate:** Criteria for assessing the output.
- **Iterate:** Process for refining the prompt based on feedback.

# Prompt refinement

> **work with a template:** 
example: [Example Template](https://raw.githubusercontent.com/OVGU-VET-TechEd/Self_Learning_Nuggets_AI_Basics/refs/heads/main/Self_Learning_Nugget_Outlinefile_V6.md)

> use a megaprompt
example: [Example Prompt](https://raw.githubusercontent.com/OVGU-VET-TechEd/Self_Learning_Nuggets_AI_Basics/refs/heads/main/Prompt_Feedback_V2.md)


Other techniwues:
> **Chain of Thought (CoT)**

Chain of Thought prompting is a technique that encourages the AI to break down complex tasks into smaller, manageable steps. This approach helps the AI to reason through the problem and arrive at a more accurate solution.

> **Tree of Thought (ToT)**

Tree of Thought prompting is a more advanced version of Chain of Thought prompting. It allows the AI to explore multiple branches of reasoning simultaneously, leading to more comprehensive and nuanced outputs.


> **If there is time: ** check out KI Campus for more prompt options
[KI Campus](https://)

**Other promptsupport: **
https://ai-27.com

**Libraries**

[AI for Education]()
[Microsoft Prompts for Education]()
[UNIGlobal Careers Prompt Library]()

> check the extended presentation for AI content generation: [AI content Generation](https://liascript.github.io/course/?https://raw.githubusercontent.com/LiaPlayground/content-creation-with-ai/refs/heads/main/README.md)


# Discussion and Feedback

- How satisfied are you with the content considering the time you spent
- what went alright
- what went wrong
- where do you see options to improve


## UNESCO Digital Learning Week – Resources 📘

- [AI and education: guidance for policy-makers](https://www.unesco.org/en/weeks/digital-learning)
- [Beijing Consensus on Artificial Intelligence and Education](https://www.unesco.org/en/weeks/digital-learning)
- [Recommendation on the Ethics of Artificial Intelligence](https://www.unesco.org/en/weeks/digital-learning)
- [Guidelines for ICT in education policies and masterplans](https://www.unesco.org/en/weeks/digital-learning)
- [Education and blockchain](https://www.unesco.org/en/weeks/digital-learning)
- [Gateways to Public Digital Learning](https://www.unesco.org/en/weeks/digital-learning)
- [Innovative use of technology in education: winning projects of UNESCO’s King Hamad Bin Isa Al-Khalifa Prize](https://www.unesco.org/en/weeks/digital-learning)
- [Artificial Intelligence and Inclusion, Compendium of Promising Initiatives: Mobile Learning Week 2020](https://www.unesco.org/en/weeks/digital-learning)
- [Artificial intelligence in Education, Compendium of Promising Initiatives: Mobile Learning Week 2019](https://www.unesco.org/en/weeks/digital-learning)
- [Beyond disruption: technology enabled learning futures; 2020 edition of Mobile Learning Week, 12-14 October 2020: report](https://www.unesco.org/en/weeks/digital-learning)
- [Artificial intelligence for Sustainable Development: synthesis report, Mobile Learning Week 2019](https://www.unesco.org/en/weeks/digital-learning)

> **Teacher Specifics:**

- [International Task Force on Teachers for Education 2030: Promoting and protecting teacher agency in the age of artificial intelligence 2025](https://teachertaskforce.org/knowledge-hub/promoting-and-protecting-teacher-agency-age-artificial-intelligence)

> **OECD tools**
- [OECD AI Tools] (https://oecd.ai/en/catalogue/overview)
