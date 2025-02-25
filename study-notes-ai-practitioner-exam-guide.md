# AWS Certified AI Practitioner Exam Guide

## Exam Overview

**Target Audience**: Individuals with up to 6 months of exposure to AI/ML technologies on AWS who use but do not necessarily build AI/ML solutions.

**Exam Format**:
- **Question Types**: Multiple choice, multiple response, ordering, matching, case study
- 50 scored questions and 15 unscored questions
- **Scoring**: Scaled score of 100–1,000, with a minimum passing score of 700

## Content Domains and Weightings

| Domain | Percentage |
|--------|------------|
| Fundamentals of AI and ML | 20% |
| Fundamentals of Generative AI | 24% |
| Applications of Foundation Models | 28% |
| Guidelines for Responsible AI | 14% |
| Security, Compliance, and Governance for AI Solutions | 14% |

## Domain 1: Fundamentals of AI and ML (20%)

### Key Concepts
- **Basic AI Terminology**: AI, ML, deep learning, neural networks, computer vision, NLP, model, algorithm, training, inferencing, bias, fairness, fit, LLM
- **Types of Learning**:
  - Supervised learning
  - Unsupervised learning
  - Reinforcement learning

### ML Development Lifecycle
- Data collection
- Exploratory Data Analysis (EDA)
- Data pre-processing
- Feature engineering
- Model training
- Hyperparameter tuning
- Evaluation
- Deployment
- Monitoring

### MLOps Concepts
- Experimentation
- Repeatable processes
- Scalable systems
- Managing technical debt
- Achieving production readiness
- Model monitoring
- Model re-training

### Performance Metrics
- Accuracy
- AUC
- F1 score
- Cost per user
- Development costs
- Customer feedback
- ROI

## Domain 2: Fundamentals of Generative AI (24%)

### Core Concepts
- Tokens and chunking
- Embeddings and vectors
- Prompt engineering
- Transformer-based LLMs
- Foundation models
- Multi-modal models
- Diffusion models

### Use Cases
- Image, video, and audio generation
- Text summarization
- Chatbots and conversational AI
- Translation
- Code generation
- Customer service agents
- Search enhancement
- Recommendation engines

### Foundation Model Lifecycle
- Data selection
- Model selection
- Pre-training
- Fine-tuning
- Evaluation
- Deployment
- Feedback loop

## Domain 3: Applications of Foundation Models (28%)

### Design Considerations
- Cost and efficiency
- Modality support
- Latency requirements
- Multi-lingual capabilities
- Model size and complexity
- Customization options
- Input/output length constraints

### Inference Parameters
- Temperature settings
- Input/output length management

### RAG (Retrieval Augmented Generation)
- Using external knowledge bases for accurate, up-to-date answers
- Vector database options:
  - Amazon OpenSearch Service
  - Amazon Aurora
  - Amazon Neptune
  - Amazon DocumentDB
  - Amazon RDS for PostgreSQL

### Model Customization Approaches
- Pre-training strategies
- Fine-tuning techniques
- In-context learning
- RAG implementation

### Prompt Engineering Techniques
- Context framing
- Instruction clarity
- Negative prompts
- Model latent space
- Chain-of-thought prompting
- Zero-shot prompting
- Single-shot prompting
- Few-shot prompting
- Prompt templates

## Domain 4: Guidelines for Responsible AI (14%)

### Key Features
- Bias mitigation
- Fairness principles
- Inclusivity practices
- System robustness
- Safety measures
- Veracity verification

### AWS Tools for Responsible AI
- Guardrails for Amazon Bedrock
- Amazon SageMaker Clarify
- SageMaker Model Monitor
- Amazon A2I (Augmented AI)

### Dataset Characteristics
- Inclusivity considerations
- Diversity requirements
- Curated data sources
- Balanced dataset creation

### Responsible AI Implementation
- Transparent and explainable models
- Human-centered design principles
- Comprehensive model evaluation
- Fairness and inclusivity strategies
- Data augmentation techniques
- Monitoring and auditing practices

## Domain 5: Security, Compliance, and Governance (14%)

### AWS Security Services
- IAM roles, policies, and permissions
- Data encryption strategies
- Amazon Macie for sensitive data discovery
- AWS PrivateLink for private connectivity
- AWS shared responsibility model

### Security Best Practices
- Source citation documentation
- Data origin tracking
- Secure data engineering
- Privacy-enhancing technologies
- Access control implementation
- Data integrity verification

### Security Considerations
- Application security measures
- Threat detection mechanisms
- Vulnerability management
- Infrastructure protection
- Prompt injection prevention
- Encryption (at rest and in transit)

### Governance and Compliance
- Regulatory standards (ISO, SOC, algorithm accountability laws)
- AWS compliance services:
  - AWS Config
  - Amazon Inspector
  - AWS Audit Manager
  - AWS Artifact
  - AWS CloudTrail
  - AWS Trusted Advisor

### Data Governance Strategies
- Data lifecycle management
- Comprehensive logging
- Data residency considerations
- Monitoring systems
- Observation protocols
- Retention policies

## AWS Services for AI/ML

### Core ML Services
- **Amazon SageMaker**: Comprehensive platform for building, training, and deploying ML models
  - SageMaker Data Wrangler: Data preparation
  - SageMaker Feature Store: Centralized repository for ML features
  - SageMaker Model Monitor: Monitors model quality
  - SageMaker Clarify: Bias detection in ML data and models
  - SageMaker JumpStart: Foundation model evaluation and selection
  - SageMaker Autopilot: Model prediction insights

### Generative AI Services
- **Amazon Bedrock**: Foundation model access via API

### AI Services
- **Amazon Comprehend**: NLP for entity recognition, sentiment analysis, language detection
- **Amazon Lex**: Conversational interface building
- **Amazon Polly**: Text-to-speech service
- **Amazon Transcribe**: Speech-to-text service
- **Amazon Translate**: Language translation
- **Amazon Rekognition**: Image and video analysis
- **Amazon Personalize**: Real-time personalization and recommendations
- **Amazon Textract**: Text and data extraction from scanned documents
- **Amazon Kendra**: Intelligent search applications
- **Amazon Q**: Relevant answers and content generation using company data
- **AWS DeepRacer**: Reinforcement learning platform
- **AWS AI Service Cards**: Responsible AI documentation
- **Amazon A2I**: Human review of ML predictions

## Security and Governance Deep Dive

### AWS Security Framework
- **AWS Shared Responsibility Model**: Defining security of the cloud vs. in the cloud
- **Defense-in-Depth Security**: Multiple redundant defenses
- **Least Privilege Policy**: Access restriction with short-term credentials

### Security Services
- **AWS Security Hub**: Centralized security findings dashboard
- **Amazon GuardDuty**: Threat detection
- **AWS KMS**: Data encryption and key management
- **AWS Shield Advanced**: DDoS protection
- **AWS WAF**: Web application protection
- **Amazon Security Lake**: Security data centralization

### Generative AI Risks and Mitigation
- **Prompt Risks**: Poisoning, hijacking, injection, exposure, leaking, jailbreaking
- **Data Poisoning**: Malicious/biased training data introduction
- **Hallucinations**: Managing incorrect but plausible-sounding assertions
- **Data Exfiltration**: Data ingress/egress controls using AWS Network Firewall and VPCs

## Prompt Engineering Guide

### Effective Elements
- Clear instructions
- Relevant context
- Well-formatted input data
- Output indicators

### Advanced Techniques
- **Zero-shot prompting**: Tasks without examples
- **Chain-of-thought prompting**: Logical reasoning with "Think step by step"
- **Few-shot prompting**: Including templates and example reports

### OWASP Top 10 for LLMs
1. Prompt Injection
2. Insecure Output Handling
3. Training Data Poisoning
4. Model Denial of Service
5. Supply Chain Vulnerabilities
6. Sensitive Information Disclosure
7. Insecure Plugin Design
8. Excessive Agency
9. Improper Access Control
10. Unsafe Model Deployment

## Study Recommendations

- Focus on understanding AWS AI service capabilities and use cases
- Gain hands-on experience with key AWS AI services
- Understand security as a critical design component
- Recognize the importance of data quality in AI/ML systems
- Balance AI innovation with responsible implementation practices

## Additional Resources
- [AWS AI Practitioner Exam Guide](https://psychedelic-cuticle-e74.notion.site/AWS-AI-Practitioner-AIF-C01-10386c7395e780e89ea4c70bb061451b)
