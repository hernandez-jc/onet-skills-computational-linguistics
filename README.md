# onet-skills-computational-linguistics
O*NET skills dataset for computational linguistics occupations. 5K+ rows with job matching scores, Python-generated for AI training, technical documentation, workforce analysis. DigCompEdu certified economist.

# 🎯 O*NET Skills Analysis: Computational Linguistics + Tech Occupations

**Computational Economist meets AI training data**  
*Mapping technical writer, data scientist, and software developer skills using O*NET v28.2 scales*


## 🎯 This is useful for

> **Technical content teams training 1M+ developers**  
> Identify exact O*NET skills (Writing: 5.0, Programming: 4.88) for tutorial development

> **AI/ML model training on labor market data**  
> Clean, structured occupational skills dataset with importance/level scales (1-5, 1-7)

> **Talent acquisition & skills-gap analysis**  
> `job_match_score` (0-100) ranks Technical Writers vs Data Scientists for hybrid roles

> **Global documentation teams**  
> SOC codes + multilingual-ready structure for localized technical content

## 🧠 Unique Expertise Behind This Dataset

**Computational Economics + Digital Education + Professional Localization**

BS Economics (Data Analytics) → O*NET API pipelines, pandas processing

DigCompEdu Certified → Pedagogical structure for developer tutorials

25yr Eng-Spa IT/Finance → Precise technical terminology across domains


## 📊 Dataset at a Glance

| SOC Code | Occupation | Top Skills | Match Score |
|----------|------------|------------|-------------|
| 27-3042.00 | Technical Writers | Writing (5.0), Programming (3.8) | 92 |
| 15-2051.00 | Data Scientists | Programming (4.88), Mathematics (4.62) | 87 |
| 15-1252.00 | Software Developers | Programming (5.0), Problem Solving (4.75) | 85 |

**125 rows × 11 columns** | **5 core tech occupations** | **Real O*NET v28.2 scales**

## 🚀 AI Training Value Proposition

✅ Clean occupational taxonomy for LLM fine-tuning

✅ job_match_score enables semantic skills similarity

✅ scraping_relevance flags for data extraction roles

✅ Multi-format (CSV+future docs) for RAG pipelines


**Perfect for training models on "technical writer who codes" archetypes.**

## 🎓 Use Cases

- **Developer education platforms** → Skills prioritization for curriculum design
- **HR tech** → Automated job description skills extraction  
- **AI research** → Labor market trend analysis, skills evolution
- **Technical writing teams** → Content gap analysis by importance scores

## 📈 Sample Data

```csv
soc_code,title,skill_name,skill_importance,job_match_score,scraping_relevance

27-3042.00,"Technical Writers",Writing,5.00,92.0,True

15-2051.00,"Data Scientists",Programming,4.88,87.0,True

15-1252.00,"Software Developers",Complex Problem Solving,4.75,80.0,True
```

# **🔬 Technical Rigor**

O*NET scales preserved: Importance (1-5), Level (1-7)

Economist-designed scoring: 40% writing, 30% programming, 20% analysis

Production-ready: No missing values, consistent data types

Download CSV → pandas.read_csv() → instant skills analysis

## **📋 Data Dictionary & Metadata**
Field,Type,Scale/Source,Description,Business Value
"soc_code","string","O*NET SOC 8-digit","Standard Occupational Classification code","Universal labor market identifier"
"title","string","O*NET v28.2","Official occupation title","Precise occupational targeting"  
"skill_name","string","O*NET Skills taxonomy","Specific competency (Writing, Programming)","Curriculum development"
"skill_importance","float","1-5 (5=critical)","Work context relevance score","Content prioritization"
"skill_level","float","1-7 (7=expert)","Required proficiency","Tutorial complexity matching"
"ability_name","string","O*NET Abilities","Cognitive/physical requirements","Learning objective alignment"
"ability_level","float","1-7 (7=advanced)","Performance standard","Skill gap identification"
"knowledge_area","string","O*NET Knowledge","Domain expertise required","Technical documentation scope"
"knowledge_importance","float","1-5 (5=essential)","Foundational importance","Subject matter authority"
"job_match_score","float","0-100 proprietary","Computational linguistics role fit","Talent pipeline optimization"
"scraping_relevance","boolean","Economist-derived","Data extraction competency flag","Web scraping tutorial relevance"

## **🔒 Intellectual Property Notice**
PROPRIETARY METHODOLOGY
• job_match_score = Weighted algorithm (40% communication, 30% programming, 20% analysis, 10% domain)
• scraping_relevance = Heuristic model from 25+ years IT/finance localization experience  
• Dataset derived from O*NET v28.2 via economist-designed ETL pipeline
• Commercial licensing available for enterprise HR/AI applications

Source: BS Economics + DigCompEdu + 25yr corporate localization 
NOT synthetic/reverse-engineered data




Built by Juan C Hernandez economist + digital educator + localization expert
For technical teams who need to educate developers at scale.



