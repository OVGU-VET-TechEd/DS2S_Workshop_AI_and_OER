<!--
author: Hannes Tegelbeckers
email: hannes.tegelbeckers@ovgu.de
version: 1.0.0
language: en
narrator: US English Female
comment: Interactive 90-minute workshop on AI applications in TVET education for Sri Lankan teachers
logo: https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Tensorflow_logo.svg/1915px-Tensorflow_logo.svg.png

link: https://raw.githubusercontent.com/OVGU-VET-TechEd/Integrating_AI_in_TVET_UNESCO/refs/heads/main/Vorlage.css

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

@aiDemo: <div class="ai-tool-demo">**🤖 AI Demo:** @0<br>**🛠️ Tool:** @1<br>**🔗 Try it:** [Click here](@2)</div>

@sectorCard: <div class="sector-card">**@0**<br>@1</div>

@resourceLink: <a href="@1" class="resource-link" target="_blank">@0</a>

-->
# .

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
  <img src="https://licensebuttons.net/l/by-sa/4.0/80x15.png" alt="CC BY-SA" style="height: 20px; vertical-align: middle;">
  <a href="https://creativecommons.org/licenses/by-sa/4.0/" style="margin-left: 5px; text-decoration: none;">CC BY-SA 4.0</a>
</div>

---


# 🎯 Course Goals

📌 **Learning Objectives:**

- Outline the context and framework for AI use in Open Educational Resources
- Update and expand your AI toolbox with practical applications
- Master text-based approaches (Markdown) for creating teaching and learning materials
- Experience hands-on creation with LiaScript and AI integration

---


## 🤖 What is AI?

🔍 **Current Reality:**

- No universally accepted definition exists
- We're primarily discussing **probability machines**
- AI learns from past data and presents historical patterns

🧠 **Human Factor:**

- We attribute understanding or consciousness to generated text where none exists
- Critical consideration: What processes do we actually want to automate?

### 🎯 AI Excellence Examples

✅ AI excels in specific tasks:

- 🏥 Spotting cancer in medical imaging
- 🌾 Assessing crop quality in agriculture
- 🔧 Quality control in welding processes
- 🚗 Autonomous vehicle navigation
- 📊 Financial fraud detection
- 🎵 Music composition and analysis

---


## 📚 Open Educational Resources (OER)

### 🌍 Definition and Scope (2019)

**Open Educational Resource (OER)** 

- *Dubai Declaration*:
> Learning, teaching, and research materials in any format and medium that reside in the public domain or under copyright but have been released under an **open license**, permitting no-cost access, reuse, repurpose, adaptation, and redistribution by others.

🎯 **Key Features:**

- 📖 Includes textbooks, multimedia, course materials
- 🤝 Prioritizes inclusivity, equity, and collaboration
- 🤖 Enhanced by AI for better accessibility and adaptability

### 🔑 Open License Framework

**Open License** = Legal tool enabling:

- ✅ Maintain creator ownership
- ✅ Specify usage terms for others
- ✅ Enable free use, reuse, adaptation, and redistribution
- ✅ Ensure proper attribution
- ⚖️ **New Challenge:** Clarify AI training data usage rights

### 📋 Key OER Declarations

🔗 **Ljubljana Declaration:**
[UNESCO OER Ljubljana Recommendation](https://www.unesco.org/en/legal-affairs/oer-recommendation)

🔗 **UNESCO 2019 Recommendation:**
[UNESCO OER Recommendation](https://unesdoc.unesco.org/ark:/48223/pf0000373755)
*Note: Governments report implementation every 4 years*

🔗 **Dubai Declaration:**
[Dubai OER Declaration](https://www.unesco.org/en/articles/dubai-declaration-open-educational-resources)

### 🔓 Open Source AI Systems

**Four Essential Freedoms:**

1. **Use** - Deploy for any purpose
2. **Study** - Examine how it works
3. **Modify** - Adapt to your needs
4. **Share** - Distribute improvements

**Technical Requirements:**

- 🏋️ **Open Weights** - Model weights and parameters
- 💻 **Open Code** - Training source code and dataset creation code
- 📊 **Open Data** - Complete training data list (when legally permitted)

🔗 [Open Source AI Definition](https://opensource.org/ai/open-source-ai-definition)

---


## 🧑‍🏫 UNESCO AI Framework for Teachers

| Competency | 📖 Acquire | 🔍 Deepen | 🚀 Create |
|------------|---------|--------|--------|
| **🧠 Human-centered Mindset** | Critically reflect on AI benefits, limitations and risks in local settings | Apply human-centered principles in AI tool selection | Design AI-enhanced experiences prioritizing human agency |
| **⚖️ Ethics of AI** | Understand basic AI ethical principles | Analyze ethical implications of AI in education | Develop ethical guidelines for AI use in teaching |
| **🔧 AI Foundations & Applications** | Learn basic AI concepts and educational tools | Integrate AI tools into teaching practice | Create innovative AI-enhanced learning solutions |
| **🎓 AI Pedagogy** | Understand AI's role in pedagogy | Adapt teaching methods with AI support | Design AI-integrated pedagogical approaches |
| **📈 AI for Professional Learning** | Use AI for personal professional development | Collaborate with AI for continuous learning | Lead professional development in AI literacy |

🔗 [UNESCO AI Competency Framework for Teachers 2024](https://www.unesco.org/en/digital-education/ai-future-learning)




## 💡 Why LiaScript?

**🎯 Text-Based Advantages**

- **📝 Simple Creation** - Easy to generate, edit, and share
- **🔄 Dynamic Rendering** - Interactive vs. static presentations
- **🌐 Translation Ready** - Text-based content is easily translatable
- **🔗 Platform Independent** - Works anywhere Markdown is supported

### 🤔 Strategic Considerations

**Your Data Strategy Questions:**

- 📊 What is your data strategy?
- 🏗️ How will it influence platform and system decisions?
- 🔮 How will it affect future digital ecosystem integration?
- 🎯 How will it support Learning Management Systems (LMS) implementation?
- 🤖 How will it enable Intelligent Tutoring Systems and personalized learning?
- 🏭 How will it adapt to changing industry skill requirements?


## 🛠️ AI Tool Examples

### 💬 Large Language Models (LLMs)

@aiDemo(Advanced conversational AI for research and analysis, Perplexity AI, https://perplexity.ai)

@aiDemo(Sophisticated reasoning and text generation, Claude AI, https://claude.ai)

@aiDemo(Microsoft's AI assistant with web integration, Copilot, https://copilot.microsoft.com)

@aiDemo(OpenAI's flagship conversational AI, ChatGPT, https://chat.openai.com)

### 🎨 Presentations and Creative Tools

@aiDemo(Grammar and writing enhancement, Grammarly, https://grammarly.com)

@aiDemo(Visual presentation creation with AI, Napkin AI, https://napkin.ai)

@aiDemo(Interactive notebook for AI experiments, LM Notebook, https://lmnotebook.com)

### 💻 Local AI Implementation

**GUI-Based Solutions:**

@resourceLink(GPT4ALL, https://gpt4all.io)
@resourceLink(Ollama GUI, https://ollama.ai)
@resourceLink(Hugging Face Spaces, https://huggingface.co/spaces)

**Command Line Solutions:**
@resourceLink(Ollama CLI, https://ollama.ai)

### 🎭 Avatar Generation

@aiDemo(AI-powered video avatar creation, HeyGen AI, https://heygen.com)

---

--{{6}}--
## 📝 Refresh: Prompting Essentials

### 🤔 What is a Prompt?
A prompt is your instruction or query to an AI system - the input that guides the AI's response.

### 🎯 Google's 5-Step Framework

**Effective Prompting Structure:**

1. **📋 Task:** Clearly define what the AI should do
2. **🌍 Context:** Provide background information and relevant details
3. **📚 References:** Include external sources or materials to consider
4. **✅ Evaluate:** Set criteria for assessing the output quality
5. **🔄 Iterate:** Process for refining based on feedback

### 🧠 Advanced Techniques

**🔗 Chain of Thought (CoT):**
Encourage step-by-step reasoning through complex problems.

**🌳 Tree of Thought (ToT):**
Enable exploration of multiple reasoning branches simultaneously for comprehensive analysis.


## 🛠️ Hands-On Workshop

### 🎯 Create Your Self-Learning Tool

**Step-by-Step Process:**

1. **🎯 Define Goals:** Set clear learning objectives
2. **📋 Choose Methods:** Select appropriate teaching approaches  
3. **🔧 Select Tools:** Pick interactive elements and features
4. **🤖 Choose LLM:** Select and justify your AI tool choice
5. **💻 Build in LiaScript:** Create your self-learning resource
6. **🚀 Test & Deploy:** Use [LiaScript Live Editor](https://liascript.github.io/LiveEditor/)

### 📝 Template Resources

🔗 **Starting Template:** [Self-Learning Template](https://raw.githubusercontent.com/OVGU-VET-TechEd/DS2S_Workshop_AI_and_OER/refs/heads/main/Nugget_Outline_Example_DS2S.md)

🔗 **Mega-Prompt Example:** [Advanced Prompting Guide](https://raw.githubusercontent.com/OVGU-VET-TechEd/DS2S_Workshop_AI_and_OER/refs/heads/main/Megaprompt_Outline_Example_DS2S.md)


## 🔧 Prompt Refinement Techniques

### 📚 Additional Resources

🔗 **KI Campus:** [AI Prompting Course](https://ki-campus.org)
🔗 **AI-27 Prompt Support:** [Prompting Tools](https://ai-27.com)

### 📖 Prompt Libraries

@resourceLink(AI for Education Library, https://www.aiforeducation.io)
@resourceLink(Microsoft Education Prompts, https://education.microsoft.com/en-us/resource/9c8f)
@resourceLink(UNIGlobal Careers Prompts, https://www.uniglobalcareers.com/ai-prompts)

### 🎥 Extended Learning

🔗 **Comprehensive Guide:** [AI Content Generation with LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/LiaPlayground/content-creation-with-ai/refs/heads/main/README.md)


## 💬 Discussion and Feedback

### 🤔 Reflection Questions

**📊 Satisfaction Assessment:**

- How satisfied are you with the content considering the time invested?
- What aspects worked well for your learning?
- Which areas need improvement?
- Where do you see opportunities for enhancement?

### 🚀 Future Applications

**🎯 Consider:**

- How will you implement these tools in your teaching?
- What additional support do you need?
- Which concepts require further exploration?

---

--{{10}}--
## 📚 UNESCO Digital Learning Resources

### 🎓 Policy and Guidance Documents

@resourceLink(AI and Education: Guidance for Policy-makers, https://www.unesco.org/en/articles/artificial-intelligence-education-guidance-policy-makers)

@resourceLink(Beijing Consensus on AI and Education, https://www.unesco.org/en/articles/beijing-consensus-artificial-intelligence-and-education)

@resourceLink(UNESCO Ethics of AI Recommendation, https://www.unesco.org/en/artificial-intelligence/recommendation-ethics)

@resourceLink(ICT in Education Policy Guidelines, https://www.unesco.org/en/education/digital-transformation/guidelines-policy)

### 🔗 Specialized Resources

@resourceLink(Education and Blockchain, https://www.unesco.org/en/articles/blockchain-education)

@resourceLink(Gateways to Public Digital Learning, https://www.unesco.org/en/education/digital-transformation/gateways)

@resourceLink(King Hamad Prize Winners, https://www.unesco.org/en/prizes-fellowships/hamad-bin-isa-al-khalifa)

### 📊 Research Compendiums

@resourceLink(AI and Inclusion Initiatives 2020, https://www.unesco.org/en/weeks/digital-learning/2020/compendium)

@resourceLink(AI in Education Initiatives 2019, https://www.unesco.org/en/weeks/digital-learning/2019/compendium)

@resourceLink(Beyond Disruption Report 2020, https://www.unesco.org/en/weeks/digital-learning/2020/report)

### 👨‍🏫 Teacher-Specific Resources

@resourceLink(Teacher Agency in AI Age 2025, https://teachertaskforce.org/knowledge-hub/promoting-and-protecting-teacher-agency-age-artificial-intelligence)

### 🌐 OECD AI Tools

@resourceLink(OECD AI Policy Observatory, https://oecd.ai/en/catalogue/overview)

---

**🎉 Thank you for participating!**

> 🚀 *Ready to shape the future of AI-enhanced education?*
