<!--
author: {{AUTHOR_NAME}}
email: {{AUTHOR_EMAIL}}
version: {{VERSION_NUMBER}}
language: {{LANGUAGE_CODE}}
comment: {{COURSE_DESCRIPTION}}

@style
.welcome-container {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 2rem;
    margin: 1rem 0;
    border-radius: 15px;
}

.nugget-header {
    background: linear-gradient(45deg, #ff6b6b, #ffa726);
    color: white;
    padding: 1rem;
    border-radius: 10px;
    margin: 1rem 0;
    text-align: center;
}

.competency-table {
    background: white;
    border-radius: 10px;
    padding: 1rem;
    margin: 1rem 0;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.reflection-section {
    background: #f8f9fa;
    border-left: 4px solid #007bff;
    padding: 1rem;
    margin: 1rem 0;
}

@highlightCell: <span style="background-color: #e3f2fd; border: 2px solid #2196f3; padding: 0.3rem; border-radius: 3px; font-weight: bold;">@0</span>

@normalCell: <span style="padding: 0.3rem;">@0</span>
@end

-->

# {{COURSE_TITLE}}

## Virtual Training Nugget {{NUGGET_NUMBER}}

<div style="text-align: center; background: #f0f0f0; padding: 1rem; border-radius: 10px; margin: 1rem 0;">

**{{NUGGET_TITLE}}**

Based on the UNESCO AI Competency Framework for Teachers

*{{ACADEMIC_REFERENCE}}*

</div>

---

## Welcome & Course Overview

<div class="welcome-container">

**Welcome to {{MAIN_TOPIC}}**

> **Course Structure:**
- **Duration:** {{COURSE_DURATION}}
- **Number of Nuggets:** {{NUMBER_OF_NUGGETS}}
- **Target Level:** {{COMPETENCY_LEVELS}}
- **Time per Nugget:** {{TIME_INVESTMENT}}

> **Learning Approach:**
{{COURSE_INTENTION_TEXT}}

</div>


**Current Focus:** {{CURRENT_LEARNING_AREA}}


---

# Nugget {{NUGGET_NUMBER}}: {{NUGGET_SUBTITLE}}

<div class="nugget-header">
**{{NUGGET_TITLE}}**
<br>
Level: {{COMPETENCY_LEVEL}} | Duration: {{NUGGET_DURATION}}
</div>

## Learning Objectives

By the end of this nugget, you will be able to:

{{#LEARNING_OBJECTIVES}}
{{OBJECTIVE_NUMBER}}. **{{ACTION_VERB}}** {{LEARNING_OUTCOME}}
{{/LEARNING_OBJECTIVES}}

---

## Core Content

> **Key Concept: {{KEY_CONCEPT}}**

{{CONCEPT_DEFINITION}}

**Essential Elements:**
{{#CORE_ELEMENTS}}
- **{{ELEMENT_TITLE}}:** {{ELEMENT_DESCRIPTION}}
{{/CORE_ELEMENTS}}

---

## Practical Application

> **Scenario: {{SCENARIO_DESCRIPTION}}**

**{{CHARACTER_NAME}}**, a {{PROFESSION}}, needs to {{CHALLENGE_DESCRIPTION}}.

**Your Task:** {{SCENARIO_QUESTION}}

### Activity: {{ACTIVITY_TITLE}}

**Instructions:** {{ACTIVITY_INSTRUCTIONS}}

    [[___]]
    **{{INPUT_FIELD_LABEL}}:** {{INPUT_FIELD_HINT}}

---

## Knowledge Check

> **Question: {{QUESTION_TOPIC}}**

{{QUESTION_TEXT}}

    [( )] {{OPTION_1}}
    [(X)] {{OPTION_2}}
    [( )] {{OPTION_3}}
    [( )] {{OPTION_4}}

---

## Reflection

<div class="reflection-section">

**💭 Take a moment to reflect:**

    [[___]]
    **{{REFLECTION_PROMPT_1}}**

    [[___]]
    **{{REFLECTION_PROMPT_2}}**

**💡 Key Insight:**

    [[___]]
    **{{INSIGHT_PROMPT}}**

</div>

---

## Resources & Next Steps

> **Essential Resources:**
{{#ESSENTIAL_RESOURCES}}
- [{{RESOURCE_TITLE}}]({{RESOURCE_URL}})
{{/ESSENTIAL_RESOURCES}}

> **Tools to Explore:**
{{#PRACTICE_TOOLS}}
- **{{TOOL_NAME}}:** {{TOOL_DESCRIPTION}} - [Try it]({{TOOL_URL}})
{{/PRACTICE_TOOLS}}

### ✅ Completion Checklist

{{#COMPLETION_CRITERIA}}
- [ ] {{COMPLETION_ITEM}}
{{/COMPLETION_CRITERIA}}

### 🎯 Coming Next

**Nugget {{NEXT_NUGGET_NUMBER}}:** {{NEXT_NUGGET_TITLE}}

{{NEXT_NUGGET_PREVIEW}}

---

## Course Navigation

{{#COURSE_NUGGETS}}
{{NUGGET_NUMBER}}. [{{NUGGET_TITLE}}]({{NUGGET_URL}}) - {{NUGGET_STATUS}}
{{/COURSE_NUGGETS}}

---

**🎉 Congratulations on completing Nugget {{NUGGET_NUMBER}}!**

> *{{CLOSING_INSPIRATION_MESSAGE}}*

**Contact & Support:**
📧 {{CONTACT_EMAIL}} | 🌐 {{COURSE_PORTAL_URL}}
