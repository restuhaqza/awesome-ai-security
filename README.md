# Awesome AI Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome resources, tools, research papers, and projects related to AI Security. This repository aims to provide a comprehensive collection of information at the intersection of Artificial Intelligence and Security, helping researchers, practitioners, and enthusiasts stay up-to-date with the latest developments in this rapidly evolving field.

## Contents
- [Frameworks and Standards](#frameworks-and-standards)
- [Tools and Frameworks](#tools-and-frameworks)
- [Research Papers](#research-papers)
- [Conferences and Events](#conferences-and-events)
- [Blogs and Articles](#blogs-and-articles)
- [Community Resources](#community-resources)
- [Learning Resources](#learning-resources)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Books](#books)
- [Organizations and Companies](#organizations-and-companies)
- [Notable Incidents and Case Studies](#notable-incidents-and-case-studies)
- [Key Topics](#key-topics)
- [Contributing](#contributing)

## Frameworks and Standards
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) - A comprehensive framework for managing risks associated with AI, focusing on risk assessment, mitigation, and governance.
- [NIST AI 600-1](https://csrc.nist.gov/pubs/ai/600/1/e2023/final) - Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile.
- [ISO/IEC 23894:2023](https://www.iso.org/standard/77304.html) - Guidance on risk management for artificial intelligence.
- [ISO/IEC 42001:2023](https://www.iso.org/standard/81230.html) - Artificial Intelligence Management System.
- [Google Secure AI Framework (SAIF)](https://cloud.google.com/blog/products/identity-security/introducing-google-cloud-secure-ai-framework) - A framework for securely implementing AI systems.
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) - The most critical security risks in Large Language Model applications.
- [MITRE ATLAS](https://atlas.mitre.org/) - Adversarial Threat Landscape for Artificial-Intelligence Systems - A knowledge base of adversary tactics and techniques.
- [Microsoft AI Red Team Framework](https://learn.microsoft.com/en-us/security/ai-red-team/) - Guidelines for AI red teaming and security testing.
- [EU AI Act](https://artificialintelligenceact.eu/) - European Union's regulatory framework for AI systems.
## Tools and Frameworks

### Defensive Tools
- [ProtectAI's ModelScan](https://github.com/protectai/modelscan) - A security scanner for detecting suspicious actions in serialized ML models.
- [rebuff](https://github.com/woop/rebuff) - A prompt injection detector.
- [langkit](https://github.com/whylabs/langkit) - A toolkit for monitoring language models and detecting attacks.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - An open-source toolkit for adding programmable guardrails to LLM-based conversational systems.
- [Llama Guard](https://github.com/meta-llama/PurpleLlama/tree/main/Llama-Guard) - A safeguard model for human-AI conversations.
- [LLM Guard](https://github.com/protectai/llm-guard) - A comprehensive security toolkit for LLM applications.
- [Microsoft Presidio](https://github.com/microsoft/presidio) - Context-aware PII detection and anonymization.
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Add guardrails to LLM applications.

### Detection and Analysis
- [StringSifter](https://github.com/fireeye/stringsifter) - A tool that ranks strings based on their relevance for malware analysis.
- [PentestGPT](https://github.com/GreyDGL/PentestGPT) - An interactive pentest tool integrating with OpenAI to conduct comprehensive penetration tests.
- [garak](https://github.com/leondz/garak) - LLM vulnerability scanner - detects hallucination, data leakage, prompt injection, and more.
- [PyRIT (Python Risk Identification Toolkit)](https://github.com/Azure/PyRIT) - Microsoft's open-source framework for AI red teaming.
- [AI Exploits](https://github.com/protectai/ai-exploits) - Collection of real-world AI/ML exploits for responsibly disclosed vulnerabilities.

### Adversarial ML Tools
- [Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox) - IBM's Python library for machine learning security.
- [CleverHans](https://github.com/cleverhans-lab/cleverhans) - Library for benchmarking ML systems' vulnerability to adversarial examples.
- [Foolbox](https://github.com/bethgelab/foolbox) - A Python toolbox to create adversarial examples.
- [TextAttack](https://github.com/QData/TextAttack) - Framework for adversarial attacks, data augmentation, and model training in NLP.
- [AdvBox](https://github.com/advboxes/AdvBox) - Toolbox to generate adversarial examples that fool neural networks.
- [Counterfit](https://github.com/Azure/counterfit) - Microsoft's CLI to automate security testing of AI/ML systems.

### Evasion and Injection Research
- [Adversarial Demonstration Attacks on Large Language Models](https://arxiv.org/abs/2305.14950) - Research on evasion techniques against LLMs.
- [Black Box Adversarial Prompting for Foundation Models](https://arxiv.org/abs/2302.04237) - Methods for indirect prompt injection in multi-modal LLMs.
- [DeepPayload](https://github.com/jinghangli98/DeepPayload) - Black-box backdoor attack on deep learning models through neural payload injection.
- [Prompt Injection Attacks and Defenses in LLM Applications](https://arxiv.org/abs/2310.12815) - Comprehensive study on prompt injection threats.

### Model Security Tools
- [HiddenLayer Model Scanner](https://hiddenlayer.com/solutions/model-scanner/) - Scans models for vulnerabilities and supply chain issues.
- [Robust Intelligence AI Firewall](https://www.robustintelligence.com/product-aifire) - Real-time protection configured to address model-specific vulnerabilities.
- [Lakera Guard](https://www.lakera.ai/) - Protection from prompt injections, data loss, and toxic content.
- [Caldera](https://github.com/mitre/caldera) - MITRE's cyber adversary emulation platform with AI plugins.
- [MLflow](https://github.com/mlflow/mlflow) - Platform for managing ML lifecycle with security features.
- [ClearML](https://github.com/allegroai/clearml) - ML/DL development platform with model tracking and security.

### LLM Security Benchmarks
- [HarmBench](https://github.com/centerforaisafety/HarmBench) - Standardized evaluation framework for automated red teaming.
- [SafetyBench](https://github.com/thu-coai/SafetyBench) - Comprehensive benchmark for LLM safety evaluation.
- [TrustLLM](https://github.com/HowieHwong/TrustLLM) - Comprehensive study of trustworthiness in LLMs.
- [DecodingTrust](https://github.com/AI-secure/DecodingTrust) - Platform for comprehensive assessment of GPT model trustworthiness.
- [PromptBench](https://github.com/microsoft/promptbench) - Unified library for evaluating and understanding LLMs.

## Research Papers

### Foundational Papers
- [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) - Goodfellow et al., 2014. Seminal work on adversarial examples in deep learning.
- [Crafting Adversarial Input Sequences for Recurrent Neural Networks](https://arxiv.org/abs/1604.08275) - Papernot et al., 2016. Study on adversarial attacks against RNNs.
- [Robust Physical-World Attacks on Deep Learning Models](https://arxiv.org/abs/1707.08945) - Kurakin et al., 2017. Analysis of physical-world attacks on deep learning visual classifiers.
- [Vulnerability of Deep Reinforcement Learning to Policy Induction Attacks](https://arxiv.org/abs/1701.04143) - Behzadan & Munir, 2017. Exploration of vulnerabilities in deep reinforcement learning systems.

### LLM Security Papers
- [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043) - Zou et al., 2023. Automated methods for generating adversarial attacks on LLMs.
- [Jailbroken: How Does LLM Safety Training Fail?](https://arxiv.org/abs/2307.02483) - Wei et al., 2023. Analysis of LLM safety training failures.
- [Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications](https://arxiv.org/abs/2302.12173) - Greshake et al., 2023. Indirect prompt injection attacks.
- [Poisoning Language Models During Instruction Tuning](https://arxiv.org/abs/2305.00944) - Wan et al., 2023. Data poisoning attacks on instruction-tuned models.
- [Ignore Previous Prompt: Attack Techniques For Language Models](https://arxiv.org/abs/2211.09527) - Perez & Ribeiro, 2022. Prompt injection attack taxonomy.
- [Red Teaming Language Models to Reduce Harms](https://arxiv.org/abs/2209.07858) - Ganguli et al., 2022. Methods for LLM red teaming.

### Model Security & Privacy
- [Model Inversion Attacks that Exploit Confidence Information](https://arxiv.org/abs/1506.08800) - Fredrikson et al., 2015. Privacy attacks on ML models.
- [Membership Inference Attacks Against Machine Learning Models](https://arxiv.org/abs/1610.05820) - Shokri et al., 2017. Privacy leakage through membership inference.
- [Stealing Machine Learning Models via Prediction APIs](https://arxiv.org/abs/1609.02943) - Tramèr et al., 2016. Model extraction attacks.
- [BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain](https://arxiv.org/abs/1708.06733) - Gu et al., 2017. Backdoor attacks on neural networks.

## Conferences and Events
- [NIST Trustworthy & Responsible AI Resource Center](https://www.nist.gov/topics/artificial-intelligence/ai-risk-management-framework) - Regularly updates on AI security events and workshops.
- [DEFCON AI Village](https://aivillage.org/) - Annual event focusing on AI security at DEFCON.
- [NeurIPS Workshop on Security in Machine Learning](https://secml-workshop.github.io/) - Academic workshop on machine learning security.
- [IEEE Conference on Secure and Trustworthy Machine Learning (SaTML)](https://satml.org/) - Leading academic conference on ML security.
- [CAMLIS (Conference on Applied Machine Learning for Information Security)](https://www.camlis.org/) - Applied ML security conference.
- [MLSecOps Community](https://mlsecops.com/) - Community-driven events and resources for ML security operations.
- [AI Security Summit](https://www.re-work.co/events/ai-security-summit) - Industry conference on AI security.
- [BlackHat Arsenal - AI/ML Track](https://www.blackhat.com/) - Tools and demonstrations in AI security.

## Blogs and Articles
- [Google AI Security Blog](https://ai.google/responsibility/)
- [Microsoft AI Security and Ethical AI](https://www.microsoft.com/en-us/ai/responsible-ai)
- [OpenAI Blog - AI Safety](https://openai.com/blog/tags/ai-safety)
- [Anthropic's AI Safety Research Overview](https://www.anthropic.com/research)
- [DeepMind Safety & Ethics](https://deepmind.com/safety-and-ethics)
- [Zscaler ThreatLabz AI Security Insights](https://www.zscaler.com/blogs/security-research)
- [Orca Security AI Security Blog](https://orca.security/resources/blog/category/ai-security/)
- [HiddenLayer AI Threat Research](https://hiddenlayer.com/research/) - Research on AI/ML security threats and vulnerabilities.
- [ProtectAI Blog](https://protectai.com/blog) - AI/ML security research and best practices.
- [Trail of Bits AI Security Blog](https://blog.trailofbits.com/category/ai-security/) - Security research for AI systems.
- [Lakera AI Security Blog](https://www.lakera.ai/blog) - LLM security and prompt injection research.
- [Adversa AI Blog](https://adversa.ai/blog/) - Adversarial AI and security insights.
- [Robust Intelligence Blog](https://www.robustintelligence.com/blog) - AI security and model validation.
- [Simon Willison's Weblog - AI Security](https://simonwillison.net/tags/security/) - Practical insights on LLM security.

## Community Resources
- [OWASP AI Security and Privacy Guide](https://owasp.org/www-project-ai-security-and-privacy-guide/) - Comprehensive guide to AI security and privacy.
- [OWASP Machine Learning Security Top 10](https://mltop10.info/) - Top 10 ML security risks.
- [ENISA Multilayer Framework for Good Cybersecurity Practices for AI](https://www.enisa.europa.eu/publications/multilayer-framework-for-good-cybersecurity-practices-for-ai)
- [MLSecOps Top 10 by Institute for Ethical AI & Machine Learning](https://ethical.institute/security.html)
- [AI Security Community on Discord](https://discord.gg/aisecurity) - Active community discussing AI security topics.
- [r/MLSecOps](https://www.reddit.com/r/mlsecops/) - Reddit community for ML security operations.
- [Awesome LLM Security](https://github.com/corca-ai/awesome-llm-security) - Curated list of LLM security resources.
- [Awesome AI Security](https://github.com/DeepSpaceHarbor/Awesome-AI-Security) - Another curated list of AI security resources.
- [Awesome ML for Cybersecurity](https://github.com/jivoi/awesome-ml-for-cybersecurity) - ML applications in cybersecurity.
- [AI Incident Database](https://incidentdatabase.ai/) - Database of AI system failures and incidents.
- [ML Commons AI Safety Working Group](https://mlcommons.org/working-groups/ai-safety/) - Collaborative effort for AI safety.

## Learning Resources

### Courses and Tutorials
- [Stanford CS329T: Trustworthy ML](https://web.stanford.edu/class/cs329t/) - Stanford course on ML trustworthiness and security.
- [MIT 6.S897: Machine Learning for Healthcare](https://mlhc.mit.edu/) - Includes security and privacy considerations.
- [Coursera: AI For Everyone](https://www.coursera.org/learn/ai-for-everyone) - Introduction to AI with ethical considerations.
- [DeepLearning.AI: AI Security Specialization](https://www.deeplearning.ai/) - Courses on securing AI systems.
- [Adversarial Machine Learning Tutorial](https://adversarial-ml-tutorial.org/) - Comprehensive tutorial on adversarial ML.
- [Practical AI Security: Attacks, Defenses, and Applications](https://academy.8ksec.io/course/practical-ai-security) - Course on AI security.

### Workshops and Labs
- [AI Village CTF](https://www.kaggle.com/competitions/ai-village-ctf) - Capture the Flag competitions focused on AI security.
- [Microsoft Learn: Responsible AI](https://learn.microsoft.com/en-us/training/paths/responsible-ai-business/) - Training path for responsible AI.
- [Google's Secure AI Framework Training](https://cloud.google.com/security/ai) - Security training for AI systems.
- [AI/LLM Exploitation Challenges](https://academy.8ksec.io/course/ai-exploitation-challenges) - Exploitation challenges focused on AI security.

### Video Resources
- [Rob Miles - AI Safety](https://www.youtube.com/@RobertMilesAI) - YouTube channel on AI safety.
- [Two Minute Papers - AI Security Topics](https://www.youtube.com/@TwoMinutePapers) - Academic paper summaries including security.
- [Yannic Kilcher - ML Security Papers](https://www.youtube.com/@YannicKilcher) - Deep dives into ML research papers.

## Datasets and Benchmarks

### Security Datasets
- [Adversarial Robustness Benchmark](https://github.com/google-research/google-research/tree/master/adversarial_robustness) - Benchmarks for adversarial robustness.
- [ImageNet-A](https://github.com/hendrycks/natural-adv-examples) - Natural adversarial examples dataset.
- [MNIST-C](https://github.com/google-research/mnist-c) - Corrupted MNIST for robustness testing.
- [TrojAI](https://pages.nist.gov/trojai/) - NIST dataset for detecting trojaned AI models.
- [AI Security Datasets Collection](https://github.com/shreyashankar/datasets-for-machine-learning-security) - Curated list of ML security datasets.

### LLM Benchmarks
- [HELM](https://crfm.stanford.edu/helm/) - Holistic Evaluation of Language Models including safety.
- [ToxiGen](https://github.com/microsoft/TOXIGEN) - Dataset for toxic language generation.
- [RealToxicityPrompts](https://allenai.org/data/real-toxicity-prompts) - Prompts for evaluating toxicity in LLMs.
- [AdvGLUE](https://adversarialglue.github.io/) - Adversarial GLUE benchmark.
- [JailbreakBench](https://jailbreakbench.github.io/) - Benchmark for LLM jailbreak attacks.

## Books

### Technical Books
- **"Adversarial Robustness for Machine Learning"** by Pin-Yu Chen et al. - Comprehensive guide to adversarial ML.
- **"Privacy-Preserving Machine Learning"** by J. Morris Chang et al. - Techniques for privacy in ML.
- **"Hands-On Machine Learning with Scikit-Learn and TensorFlow"** by Aurélien Géron - Includes security considerations (Chapter 17).
- **"Machine Learning Security"** by Clarence Chio & David Freeman - Practical guide to ML security.
- **"AI Safety: Solving the Control Problem"** by Roman Yampolskiy - Focus on AI safety and control.

### General AI Security
- **"The Alignment Problem"** by Brian Christian - Machine learning and human values.
- **"Human Compatible"** by Stuart Russell - AI safety and beneficial AI.
- **"Artificial Intelligence Safety and Security"** edited by Roman V. Yampolskiy - Collection of research on AI safety.
- **"Deep Learning"** by Ian Goodfellow et al. - Includes adversarial examples (Chapter 20.13).

## Organizations and Companies

### Research Organizations
- [OpenAI Safety Team](https://openai.com/safety) - Research on AI safety and alignment.
- [Anthropic](https://www.anthropic.com/) - AI safety and research company.
- [DeepMind Safety Research](https://www.deepmind.com/safety-and-ethics) - Safety and ethics in AI research.
- [AI Safety Institute (UK)](https://www.gov.uk/government/organisations/ai-safety-institute) - UK government AI safety research.
- [Center for AI Safety (CAIS)](https://www.safe.ai/) - Nonprofit focused on AI safety research.
- [Future of Life Institute](https://futureoflife.org/cause-area/artificial-intelligence/) - AI safety advocacy and research.
- [Machine Intelligence Research Institute (MIRI)](https://intelligence.org/) - Mathematical research on AI safety.
- [Partnership on AI](https://partnershiponai.org/) - Multi-stakeholder organization on AI best practices.

### Security Companies
- [ProtectAI](https://protectai.com/) - AI/ML security platform and tools.
- [HiddenLayer](https://hiddenlayer.com/) - ML security and model protection.
- [Robust Intelligence](https://www.robustintelligence.com/) - AI security and validation platform.
- [Lakera](https://www.lakera.ai/) - LLM security and prompt injection protection.
- [Adversa AI](https://adversa.ai/) - AI security and red teaming services.
- [Credo AI](https://www.credo.ai/) - AI governance and risk management.
- [Arthur AI](https://www.arthur.ai/) - ML monitoring and security.
- [Fiddler AI](https://www.fiddler.ai/) - ML monitoring and explainability.

### Industry Initiatives
- [AI Alliance](https://thealliance.ai/) - Open community for AI advancement and safety.
- [MLCommons](https://mlcommons.org/) - Engineering consortium for ML innovation.
- [Linux Foundation AI & Data](https://lfaidata.foundation/) - Open source AI projects.

## Notable Incidents and Case Studies

### High-Profile Incidents
- **Tay Chatbot (2016)** - Microsoft's chatbot corrupted through adversarial inputs in 24 hours.
- **ImageNet Adversarial Attacks (2016-2018)** - Demonstrations of fooling state-of-the-art image classifiers.
- **Tesla Autopilot Incidents (2016-present)** - Various incidents highlighting ML safety concerns.
- **Clearview AI Privacy Breach (2020)** - Unauthorized facial recognition data collection.
- **GPT-3 Misuse Cases (2020-2022)** - Phishing, misinformation, and code generation exploits.
- **ChatGPT Jailbreaks (2023)** - Various prompt injection and jailbreak techniques discovered.
- **Bing Chat Sydney Incident (2023)** - Unintended behavior and prompt injection vulnerabilities.
- **Google Bard Data Leak (2023)** - Privacy concerns with conversation data.
- **Samsung ChatGPT Data Leak (2023)** - Employees accidentally leaked confidential data to ChatGPT.
- **MITRE AI Attack Demo (2023)** - Successful adversarial attacks on production ML systems.

### Research Demonstrations
- **Robust Physical Adversarial Attacks** - Stop signs misclassified with stickers.
- **Model Extraction Attacks** - Successfully extracted commercial ML models via API queries.
- **Data Poisoning in Federated Learning** - Compromising distributed learning systems.
- **Backdoor Attacks in Image Recognition** - Trojaned models behaving normally except on trigger inputs.
- **Membership Inference Success** - Identifying training data from model behavior.

### Resources
- [AI Incident Database](https://incidentdatabase.ai/) - Comprehensive database of AI failures and incidents.
- [AVID (AI Vulnerability Database)](https://avidml.org/) - Database of AI/ML vulnerabilities.
- [NIST AI Risk Management Playbook](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook) - Case studies and lessons learned.

## Key Topics

### AI in Cybersecurity
- Threat Detection and Response
- Anomaly Detection
- Automated Security Systems
- Malware Classification
- Network Intrusion Detection
- Security Operations Center (SOC) Automation

### AI-Driven Threats
- AI-Generated Phishing
- AI-Powered Malware and Ransomware
- Deepfakes and Social Engineering
- Automated Vulnerability Discovery
- AI-Enhanced Social Engineering

### LLM-Specific Security
- Prompt Injection Attacks
- Jailbreaking Techniques
- LLM Data Poisoning
- Indirect Prompt Injection
- Plugin/Tool Security
- Context Window Attacks
- Token Smuggling

### Adversarial Machine Learning
- Evasion Attacks
- Poisoning Attacks
- Model Extraction
- Model Inversion
- Backdoor Attacks
- Adversarial Examples Generation

### Secure AI Transformation
- Data Protection in AI Systems
- AI Model Security
- Encryption for AI
- Secure Model Deployment
- ML Supply Chain Security
- Model Provenance and Integrity

### Privacy in AI
- Differential Privacy
- Federated Learning Security
- Privacy-Preserving ML
- Data Anonymization
- Membership Inference Protection

### AI Ethics and Regulation
- AI Governance Frameworks
- Compliance and Auditing
- Bias Detection and Mitigation
- Explainable AI (XAI)
- Responsible AI Development

### Additional Topics
- Zero Trust Security Models for AI
- Visual Intelligence in Security
- AI in Penetration Testing
- Red Teaming for AI Systems
- AI Safety and Alignment
- MLOps Security (MLSecOps)

## Contributing
Your contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License
This project is licensed under the [MIT License](LICENSE).

---

If you find this repository helpful, please consider giving it a star ⭐️ to show your support!

Last updated: 2025-11-04
