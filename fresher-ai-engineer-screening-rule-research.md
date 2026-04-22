# Executive Summary  

This report distills the technical criteria for screening resumes for a **Junior AI Engineer (Entry-Level)** role at Crownstack (posted via QuickLabs)【8†L93-L100】【15†L300-L309】. The job emphasizes foundational AI/ML skills (Python programming, basic machine learning concepts, familiarity with modern tools like LLMs and vector databases)【8†L93-L100】【15†L300-L309】. We derived 100 precise, measurable screening rules from the job posting and industry best practices. These rules span **Programming**, **ML/Deep Learning**, **Data Engineering**, **Tools/Platforms**, **Projects/Portfolio**, **Evaluation Metrics**, **Deployment/MLOps**, **Mathematics/Statistics**, **Code Quality/Testing**, **Datasets/Domain Knowledge**, and **Certifications/Training**. Each rule includes (1) a concise statement, (2) its importance, (3) how to check it in a CV (keywords/artefacts), and (4) a priority. For example, the posting explicitly requires “Basic Python programming” skills【8†L93-L94】, so one high-priority rule is **“CV demonstrates Python proficiency”**. Other high-priority criteria include data structures/algorithms knowledge, core ML algorithms (classification, regression), and familiarity with Git version control【8†L93-L100】【15†L300-L309】. We also include rules for common AI frameworks (scikit-learn, TensorFlow/PyTorch)【11†L263-L272】, LLM and agent tools (LangChain, vector DBs)【8†L98-L102】, cloud and MLOps fundamentals【11†L279-L282】【15†L285-L294】, and quantifiable evidence like projects, Kaggle competitions, and coding portfolios【1†L142-L149】【11†L324-L330】. Unspecified items in the posting (e.g. specific metrics or datasets) are noted as such. The final table summarizes all rules with IDs, short statements, category, and priority. The accompanying workflow diagram illustrates how automated screening rules fit into the candidate screening process.  

【Note: The job posting highlights Python, ML concepts, LLMs, Git, FastAPI/Flask, LangChain/RAG, vector DBs, and AI tools【8†L93-L100】【8†L62-L69】, so our rules heavily emphasize these areas.】  

## Programming  

- **Python Proficiency**: Checks if the CV lists Python skills or projects.  
  *Why*: Python is explicitly required (data structures, functions, OOP concepts)【8†L93-L94】. It’s the dominant AI/ML language【11†L180-L182】.  
  *How*: Look for “Python” in skills, experience, or project descriptions (e.g. using pandas, NumPy, TensorFlow, etc.).  
  *Priority*: **High** (critical requirement).  

- **Other Programming Languages**: CV lists languages like R, Java, C++, etc.  
  *Why*: Knowledge of languages such as R (for statistical work), Java or C++ (for performance) broadens applicability【11†L185-L193】. It shows adaptability.  
  *How*: Check for R, Java, C++, or similar listed under technical skills.  
  *Priority*: **Medium**.  

- **Data Structures & Algorithms**: CV mentions data structures (lists, trees, hashes) or algorithms (sorting, search, dynamic programming).  
  *Why*: Fundamental for writing efficient code and understanding ML algorithms【15†L256-L264】【8†L93-L94】. The posting values core algorithm knowledge.  
  *How*: Keywords like “algorithm”, “data structure”, “complexity”, or named algorithms (binary search, quicksort, k-means) in skills or projects.  
  *Priority*: **High**.  

- **Object-Oriented Programming (OOP)**: CV shows experience with classes, inheritance, or design patterns.  
  *Why*: OOP principles are assumed (the posting lists OOP)【8†L93-L94】. It indicates better code organization.  
  *How*: Terms like “object-oriented”, “class”, “inheritance”, or project descriptions structured with classes.  
  *Priority*: **High**.  

- **Algorithmic Projects or Contests**: CV includes algorithmic coding or hackathon experience.  
  *Why*: Participation in coding challenges or algorithm-centric projects shows problem-solving initiative【15†L256-L264】. It often correlates with strong analytical skills.  
  *How*: Look for mentions of hackathons, competitive programming, LeetCode/HackerRank/CodeChef profiles, or CS course projects focusing on algorithms.  
  *Priority*: **Medium**.  

- **Software or Coding Projects**: CV details coding projects (especially with ML/AI) or provides GitHub links.  
  *Why*: Practical projects demonstrate the ability to apply programming skills to real problems【11†L324-L330】. The posting praises a strong GitHub portfolio【1†L146-L149】.  
  *How*: Presence of a GitHub/Bitbucket link; bullet points describing projects (e.g. “Developed a Python web scraper” or “Built a sentiment analysis script in Python”).  
  *Priority*: **High**.  

- **Clean Code Practices**: CV indicates attention to code quality (coding standards, documentation).  
  *Why*: Clean, modular code is essential for maintainability. Best practices (PEP8, code reviews) are industry norms【11†L193-L197】.  
  *How*: Look for keywords like “clean code”, “PEP8”, “code review”, “linting”, or “refactoring” in skills or experience. Also note any mention of documentation, design patterns, or coding standards.  
  *Priority*: **Medium**.  

- **Version Control (Git)**: CV shows use of Git/GitHub for code management.  
  *Why*: The job explicitly lists Git/GitHub familiarity【8†L94】. Version control is mandatory for team development.  
  *How*: Check for “Git”, “GitHub”, or related terms under skills or in project descriptions (e.g. “used Git for version control”). Presence of a public GitHub profile also counts.  
  *Priority*: **High**.  

- **Unit Testing Experience**: CV mentions writing unit tests or test frameworks (e.g. pytest, JUnit).  
  *Why*: Unit testing indicates code reliability and professionalism. It’s an industry best practice and often implied by “clean, production-grade code” requirements.  
  *How*: Keywords like “unit test”, “pytest”, “unittest”, “test coverage” in skills or experience.  
  *Priority*: **Medium**.  

- **Command-Line/Scripting Skills**: CV includes experience with shell scripting or Linux/Unix.  
  *Why*: Many AI/data tasks involve CLI tools and scripting for automation. Familiarity with Linux (the typical dev environment) and Bash/Python scripts is valuable.  
  *How*: Terms like “Bash”, “shell script”, “Linux/Unix”, or projects that mention automating via scripts.  
  *Priority*: **Low**.  

## ML / Deep Learning  

- **Supervised Learning Concepts**: CV references supervised methods (classification, regression).  
  *Why*: Core ML techniques; the job lists supervised learning understanding【8†L93-L96】. It’s fundamental to many AI tasks.  
  *How*: Look for “classification”, “regression”, “supervised learning” in skills or project descriptions.  
  *Priority*: **High**.  

- **Unsupervised Learning Concepts**: CV references unsupervised methods (clustering, dimensionality reduction).  
  *Why*: Shows breadth of ML knowledge beyond supervised methods. The posting explicitly mentions clustering and unsupervised learning【8†L93-L96】.  
  *How*: Keywords “clustering”, “k-means”, “PCA”, “unsupervised” in skills or experience.  
  *Priority*: **High**.  

- **ML Algorithm Knowledge**: CV lists specific algorithms (e.g. decision trees, SVM, k-means).  
  *Why*: Knowing common algorithms indicates practical ML skill. Employers expect familiarity with algorithms like decision trees, SVMs, k-means, etc.【15†L256-L264】.  
  *How*: Presence of algorithm names (“decision tree”, “support vector machine”, “random forest”, “k-means”, etc.) in projects or skills.  
  *Priority*: **High**.  

- **Machine Learning Libraries**: CV mentions usage of libraries like scikit-learn (for ML).  
  *Why*: scikit-learn is a standard ML toolkit; proficiency accelerates model building【11†L263-L272】. It shows ability to implement ML without heavy low-level coding.  
  *How*: Look for “scikit-learn” or related terms (e.g. “sklearn pipeline”, “sklearn grid search”) in skills or project descriptions.  
  *Priority*: **High**.  

- **Deep Learning Frameworks**: CV shows experience with frameworks like TensorFlow/Keras or PyTorch.  
  *Why*: The job expects basic familiarity with deep learning frameworks【8†L98-L100】. These are essential for neural network tasks【11†L269-L273】.  
  *How*: Keywords “TensorFlow”, “Keras”, “PyTorch”, “cnn”, “rnn”, “neural network” in projects or skills.  
  *Priority*: **High**.  

- **Neural Network & Advanced Models**: CV references neural nets (CNN, RNN, Transformers).  
  *Why*: Neural networks power many AI applications (vision, NLP). The job implicitly targets LLMs/transformers, so understanding neural architectures is key【8†L99-L102】.  
  *How*: Terms like “CNN”, “RNN”, “Transformer”, “GPT”, “BERT” in project descriptions or skills.  
  *Priority*: **High**.  

- **Large Language Models (LLMs) & Agents**: CV indicates familiarity with modern LLM concepts (prompt engineering, agentic frameworks).  
  *Why*: The role specifically involves LLMs, LangChain, agentic workflows【8†L65-L69】【8†L99-L102】. Knowledge of tools like LangChain/LangGraph or usage of GPT/Claude is highly relevant.  
  *How*: Look for “GPT”, “BERT”, “Transformer”, “LLM”, “LangChain”, “agents”, or similar in skills or projects.  
  *Priority*: **High**.  

- **Retrieval-Augmented Generation (RAG) & Vector DBs**: CV mentions RAG pipelines or vector databases (Pinecone, Chroma, Weaviate).  
  *Why*: The posting requires awareness of RAG and vector DBs【8†L99-L100】. This is a cutting-edge area for LLM-based applications.  
  *How*: Keywords like “RAG”, “embeddings”, “Pinecone”, “ChromaDB”, “Weaviate”, “semantic search” on CV.  
  *Priority*: **Medium**.  

- **AI Agent Concepts**: CV references multi-agent or agent-based AI frameworks.  
  *Why*: The job values familiarity with AI agents and agentic workflows【8†L100-L102】. It shows understanding of complex AI systems.  
  *How*: Look for “agent”, “multi-agent”, “LangGraph”, or project descriptions like “built a conversational agent”.  
  *Priority*: **Medium**.  

- **Generative Models**: CV indicates knowledge of generative AI (GANs, VAEs, LLMs).  
  *Why*: Generative AI (e.g., GANs, generative transformers) is a focus of the role. Demonstrates familiarity with modern AI.  
  *How*: Terms like “GAN”, “autoencoder”, “GPT”, “transformer”, or projects about generative tasks.  
  *Priority*: **Medium**.  

- **Hyperparameter Tuning/Model Selection**: CV includes experience tuning models (grid search, random search).  
  *Why*: Optimizing model performance is critical. Screening often looks for “hyperparameter tuning” skills or “GridSearchCV” usage.  
  *How*: Keywords “hyperparameter”, “GridSearchCV”, “cross-validation”, “Bayesian optimization”, etc., in projects or methods.  
  *Priority*: **Medium**.  

- **End-to-End ML Lifecycle**: CV suggests involvement in the complete model pipeline (training to deployment).  
  *Why*: The job includes model training, evaluation, and deployment【8†L128-L136】. Experience in an end-to-end ML project shows readiness for such tasks.  
  *How*: Phrases like “end-to-end ML pipeline”, or project descriptions covering data collection through model serving.  
  *Priority*: **Medium**.  

- **Kaggle or Competition Experience**: CV shows participation in ML competitions (e.g. Kaggle).  
  *Why*: The posting cites Kaggle involvement as a plus【1†L146-L149】. Competitions demonstrate problem-solving and coding under real datasets.  
  *How*: Presence of Kaggle profile link, contest rankings, or mention of competition results/projects.  
  *Priority*: **Medium**.  

- **Specialized ML Areas**: CV indicates focus areas like NLP or computer vision.  
  *Why*: Role deals with LLMs (NLP) and possibly vision tasks. Domain specialization (e.g. NLP projects) aligns with advanced topics.  
  *How*: Keywords “NLP”, “computer vision”, “CV”, “BERT”, “image recognition” in skills/projects.  
  *Priority*: **Medium**.  

- **Statistical/Machine Learning Theory**: CV lists understanding of overfitting, bias-variance, regularization.  
  *Why*: Indicates deeper ML theory knowledge (normal/principle for any ML engineer).  
  *How*: Terms like “overfitting”, “bias-variance”, “regularization”, “dropout”, etc.  
  *Priority*: **Low**.  

## Data Engineering  

- **Data Preprocessing Skills**: CV mentions data cleaning, wrangling, or transformation.  
  *Why*: Data quality is foundational. The job explicitly mentions data collection, cleaning, preprocessing tasks【8†L62-L65】. Ability to prepare raw data is crucial.  
  *How*: Look for “data cleaning”, “preprocessing”, “data wrangling”, “imputation”, “normalization”, etc. in descriptions.  
  *Priority*: **High**.  

- **Pandas/NumPy Proficiency**: CV lists experience with pandas and NumPy.  
  *Why*: Pandas/NumPy are core data manipulation libraries【11†L263-L272】. The posting expects Python for ML workflows, implying these tools.  
  *How*: Presence of “pandas”, “numpy”, or related tasks (DataFrame, ndarray) in skills or projects.  
  *Priority*: **High**.  

- **Database/SQL Experience**: CV shows use of SQL or NoSQL databases.  
  *Why*: The scribd JD mentions familiarity with SQL/NoSQL【1†L164-L166】. Data storage and retrieval skills (e.g. querying with SQL) are often needed.  
  *How*: Keywords “SQL”, “MySQL”, “PostgreSQL”, “NoSQL”, “MongoDB”, “database” under skills/experience.  
  *Priority*: **Medium**.  

- **Data Visualization**: CV indicates use of plotting libraries (Matplotlib, Seaborn).  
  *Why*: Visualization is key for analysis. Listing such tools shows ability to analyze and present data insights【11†L265-L270】.  
  *How*: “Matplotlib”, “Seaborn”, “Plotly”, “ggplot”, or “data visualization” in skills/projects.  
  *Priority*: **Medium**.  

- **ETL/Data Pipeline Tools**: CV references ETL frameworks (e.g. Apache Airflow, Kafka).  
  *Why*: Building data pipelines is often part of a data role. Even basic pipeline experience is a plus for handling AI workloads.  
  *How*: Look for “ETL”, “Airflow”, “Luigi”, “Kafka”, “Spark Streaming” in skills or project descriptions.  
  *Priority*: **Low**.  

- **Big Data Technologies**: CV mentions Spark, Hadoop or similar.  
  *Why*: Experience with big-data tools indicates ability to handle large datasets【11†L274-L278】. Not explicitly required, but beneficial.  
  *How*: “Apache Spark”, “Hadoop”, “MapReduce”, or cluster computing experience listed.  
  *Priority*: **Low**.  

- **Handling Imperfect Data**: CV shows techniques for missing data or outliers.  
  *Why*: Real-world data is messy. Demonstrating methods (imputation, normalization) is valuable.  
  *How*: Words like “imputation”, “outlier detection”, “normalization”, “feature scaling” in skills or project notes.  
  *Priority*: **Low**.  

- **Notebook Experience**: CV shows use of Jupyter or Colab.  
  *Why*: Notebooks are standard for exploratory data work. The scribd JD lists “notebooks (Jupyter/Colab)”【1†L164-L166】.  
  *How*: Explicitly “Jupyter”, “Colab”, or “notebook” in tools.  
  *Priority*: **Low**.  

- **Data Versioning/Workflow**: CV mentions structured data workflows or tools (like DVC).  
  *Why*: Tracks data changes; while niche for juniors, it indicates maturity in handling data pipelines.  
  *How*: Terms like “DVC”, “data pipeline”, “data workflow”.  
  *Priority*: **Low**.  

- **Data Storage/NoSQL**: CV lists experience with NoSQL (e.g. MongoDB, Cassandra) or cloud storage.  
  *Why*: Useful for unstructured or large-scale data handling.  
  *How*: “MongoDB”, “Firebase”, “Cassandra”, “DynamoDB” in skills.  
  *Priority*: **Low**.  

## Tools / Platforms  

- **FastAPI/Flask**: CV mentions FastAPI or Flask frameworks.  
  *Why*: The posting specifically says trainees will “learn Python frameworks like FastAPI and Flask”【8†L62-L64】 and build REST APIs. These skills are directly relevant for deploying models.  
  *How*: Check for “FastAPI”, “Flask”, “REST API”, or “web service” in skills/projects.  
  *Priority*: **Medium**.  

- **Version Control (Git/GitHub)**: CV indicates active use of Git/GitHub.  
  *Why*: Essential for collaborative development. The job lists Git/GitHub as must-have【8†L93-L94】.  
  *How*: Look for “Git”, “GitHub”, or reference to pull requests/contributions in profile. Presence of a public repo is strong evidence.  
  *Priority*: **High**.  

- **Containerization (Docker)**: CV lists Docker experience.  
  *Why*: Docker is standard for deploying consistent environments【11†L279-L282】. While not in posting, it is key MLOps knowledge.  
  *How*: Keyword “Docker” or projects deployed in Docker containers.  
  *Priority*: **Medium**.  

- **Container Orchestration (Kubernetes)**: CV mentions Kubernetes or similar.  
  *Why*: Important for scaling/deploying services. Often used in production AI.  
  *How*: “Kubernetes”, “K8s”, “EKS/GKE”, or related terms.  
  *Priority*: **Low**.  

- **Cloud Platforms (AWS/GCP/Azure)**: CV shows use of cloud services.  
  *Why*: Experience with cloud deployment (e.g. AWS SageMaker, GCP AI Platform) is valued. The posting lists cloud exposure as nice-to-have【8†L111-L112】.  
  *How*: Keywords like “AWS”, “Azure”, “GCP”, “EC2”, “S3”, “Lambda”, “Cloud Functions”, “SageMaker” etc.  
  *Priority*: **Medium**.  

- **ML Ops Tools**: CV includes MLOps/DevOps tools like MLflow or Kubeflow.  
  *Why*: Indicates understanding of productionizing ML. These tools are emerging industry standards【11†L279-L282】.  
  *How*: Look for “MLflow”, “Kubeflow”, “CI/CD”, “Jenkins”, “CircleCI” in skills or experience.  
  *Priority*: **Low**.  

- **AI/LLM Frameworks (LangChain/LangGraph)**: CV mentions LangChain, LangGraph, or similar.  
  *Why*: The role explicitly involves working with these modern LLM frameworks【8†L65-L69】【8†L98-L99】. Demonstrates cutting-edge skills.  
  *How*: Keywords “LangChain”, “LangGraph”, “agentic framework”, or project usage of these tools.  
  *Priority*: **Medium**.  

- **Vector Databases**: CV lists Pinecone, ChromaDB, or Weaviate experience.  
  *Why*: These databases support semantic search in RAG pipelines. The posting mentions them【8†L99-L100】.  
  *How*: “Pinecone”, “Chroma”, “Weaviate”, or “vector DB” in tools/experience.  
  *Priority*: **Medium**.  

- **LLM APIs & SDKs**: CV indicates use of OpenAI, Anthropic, or Google AI APIs.  
  *Why*: Exposure to LLM APIs (e.g. ChatGPT API) is explicitly required【8†L97-98】. Shows hands-on LLM work.  
  *How*: Names like “OpenAI”, “GPT-3/4”, “Claude”, “Gemini API”, or “HuggingFace Transformers” on CV.  
  *Priority*: **High**.  

- **AI Coding Assistants**: CV mentions tools like GitHub Copilot, Claude Code, etc.  
  *Why*: The posting notes comfort with AI-assisted coding tools【8†L101-L103】. While not mandatory, it shows engagement with modern dev tools.  
  *How*: “Copilot”, “CoPilot”, “Claude Code”, “Cursor AI” in skills.  
  *Priority*: **Low**.  

- **CI/CD and DevOps**: CV includes continuous integration pipelines (GitHub Actions, Jenkins).  
  *Why*: Automating tests/deployment improves code quality. Relevant for MLOps roles.  
  *How*: Look for “CI/CD”, “GitHub Actions”, “Travis CI”, “CircleCI”, “Jenkins” in tools.  
  *Priority*: **Low**.  

## Projects / Portfolio  

- **GitHub or Portfolio Link**: CV provides a link to GitHub or personal portfolio.  
  *Why*: Direct evidence of work. The posting encourages a strong GitHub portfolio【1†L146-L149】.  
  *How*: Presence of a URL to GitHub, GitLab, Bitbucket, or a personal website/portfolio.  
  *Priority*: **High**.  

- **AI/ML Projects**: CV describes completed AI/ML projects.  
  *Why*: Demonstrates hands-on experience. The posting values prior ML/AI projects【1†L142-L149】.  
  *How*: Project bullets mentioning “ML model”, “AI solution”, or specific use cases (e.g. image classifier, chatbot).  
  *Priority*: **High**.  

- **Kaggle Participation**: CV shows Kaggle competitions or notebooks.  
  *Why*: Kaggle involvement shows practical ML skill and is explicitly mentioned as a plus【1†L146-L149】.  
  *How*: Kaggle profile link or statements like “Ranked X on Kaggle” or “completed XYZ Kaggle competition”.  
  *Priority*: **Medium**.  

- **Open-Source Contributions**: CV lists contributions to open-source projects.  
  *Why*: Indicates collaboration and initiative. The posting notes open-source contributions as a plus【1†L146-L149】.  
  *How*: Mentions of pull requests, GitHub contributions, or participation in OSS projects (e.g. projects on GitHub with pull request counts).  
  *Priority*: **Medium**.  

- **Relevant Coursework/Capstones**: CV highlights academic projects or capstones in AI/ML.  
  *Why*: Shows formal training and practical work in domain.  
  *How*: Course titles or project descriptions (e.g. “Machine Learning course project” or “Capstone: Predictive analytics”).  
  *Priority*: **Medium**.  

- **Academic Projects**: CV mentions undergraduate/graduate projects involving ML.  
  *Why*: Entry-level roles often rely on academic experience. Projects like thesis or final-year projects are evidence of skill.  
  *How*: Look for “bachelor’s project”, “thesis”, or project titles involving data or ML.  
  *Priority*: **Medium**.  

- **Hackathons/Competitions**: CV includes hackathon or contest wins.  
  *Why*: Shows practical problem-solving and teamwork.  
  *How*: “Hackathon”, “Competition”, awards in relevant events in experience.  
  *Priority*: **Low**.  

- **Freelance/Consulting Projects**: CV notes any freelance work in AI/tech.  
  *Why*: Indicates real-world application and client experience.  
  *How*: Project descriptions under work experience, or “Freelance AI engineer” entries.  
  *Priority*: **Low**.  

- **Public Portfolio or Blog**: CV links to a blog or public demos.  
  *Why*: Sharing knowledge (e.g. blog posts) or interactive demos shows communication and initiative.  
  *How*: URLs to blogs (Medium, personal), Jupyter notebook links, or interactive dashboards.  
  *Priority*: **Low**.  

- **Prior Internship/Work in AI/ML**: CV lists any internships or roles in AI/ML fields.  
  *Why*: Even if entry-level, relevant internship or part-time work is a strong plus【8†L107-L110】.  
  *How*: Titles/descriptions like “Data Science Intern”, “AI research assistant”, or contract projects.  
  *Priority*: **Medium**.  

## Evaluation Metrics  

- **Classification Metrics**: CV mentions accuracy, precision, recall, F1-score.  
  *Why*: Standard metrics for classification tasks. Hiring managers expect familiarity with these【15†L300-L309】.  
  *How*: Keywords “accuracy”, “precision”, “recall”, “F1” in project results or skill lists.  
  *Priority*: **High**.  

- **Regression Metrics**: CV mentions MSE, RMSE, MAE, R².  
  *Why*: Key for regression tasks.  
  *How*: Terms like “MSE”, “mean squared error”, “R-squared”, etc.  
  *Priority*: **Medium**.  

- **Model Evaluation Techniques**: CV references cross-validation, train-test split.  
  *Why*: Indicates proper model validation approach.  
  *How*: Phrases “cross-validation”, “k-fold”, “train-test split”, “holdout set”.  
  *Priority*: **Medium**.  

- **ROC-AUC & Confusion Matrix**: CV mentions AUC-ROC or confusion matrices.  
  *Why*: Important for imbalanced data and classification diagnostics.  
  *How*: “ROC”, “AUC”, “confusion matrix” keywords.  
  *Priority*: **Medium**.  

- **Experiment Tracking**: CV includes use of tools like MLflow or TensorBoard.  
  *Why*: Demonstrates organized experiment management, valuable in ML development.  
  *How*: “MLflow”, “TensorBoard”, “comet.ml” in skills or projects.  
  *Priority*: **Low**.  

- **Overfitting/Underfitting Awareness**: CV discusses generalization (e.g., bias-variance).  
  *Why*: Shows understanding of core ML pitfalls.  
  *How*: Terms “overfit”, “underfit”, “regularization” in descriptions.  
  *Priority*: **Low**.  

- **Feature Evaluation**: CV mentions feature importance or selection (e.g. SHAP, LIME).  
  *Why*: Indicates advanced evaluation skills (model interpretability).  
  *How*: Keywords “feature importance”, “SHAP”, “LIME”.  
  *Priority*: **Low**.  

- **Benchmarking Results**: CV quantifies outcomes (e.g. “improved accuracy by 5%”).  
  *Why*: Shows results-oriented mindset. Quantified achievements are valued on resumes.  
  *How*: Look for percentages, error rates, or improvements stated in project outcomes.  
  *Priority*: **Low**.  

- **Domain-Specific Metrics**: CV mentions metrics like BLEU (NLP) or IoU (CV).  
  *Why*: Specialized metrics indicate domain expertise (e.g. NLP, vision).  
  *How*: “BLEU”, “ROUGE”, “IOU”, “PSNR” etc.  
  *Priority*: **Low**.  

- **Statistical Significance**: CV implies understanding of p-values or hypothesis testing in context of results.  
  *Why*: Though rare for juniors, it reflects a strong analytical background in validating models.  
  *How*: Terms like “p-value”, “statistical significance”.  
  *Priority*: **Low**.  

## Deployment / MLOps  

- **Docker Expertise**: CV indicates building or using Docker containers.  
  *Why*: Docker is fundamental for deploying and sharing ML applications【11†L279-L282】. It ensures reproducibility.  
  *How*: “Dockerfile”, “containerized”, “Docker” in skills or project environment descriptions.  
  *Priority*: **Medium**.  

- **Kubernetes/Orchestration**: CV lists Kubernetes or cloud orchestration.  
  *Why*: For production-scale deployment of models, orchestration knowledge is a plus【11†L279-L282】.  
  *How*: Keywords “Kubernetes”, “K8s”, “EKS”, “GKE”, “Azure AKS”.  
  *Priority*: **Low**.  

- **API/Model Serving**: CV shows experience deploying models via REST APIs or similar (e.g. using FastAPI).  
  *Why*: The role specifically involves building APIs with FastAPI to serve models【8†L175-L177】.  
  *How*: “API”, “Flask”, “FastAPI”, “RESTful service”, or mention of “deployed model as API”.  
  *Priority*: **High**.  

- **Cloud Deployment Experience**: CV includes AWS SageMaker, Azure ML, or GCP AI Platform.  
  *Why*: Demonstrates ability to deploy ML in cloud environments.  
  *How*: Terms like “SageMaker”, “AWS Lambda”, “Azure ML”, “GCP AI” in projects/skills.  
  *Priority*: **Medium**.  

- **CI/CD Pipelines**: CV includes setting up CI/CD for ML (e.g. GitHub Actions, Jenkins).  
  *Why*: Continuous integration of ML code ensures reliability and faster iteration.  
  *How*: Look for “CI/CD pipeline”, “GitHub Actions”, “Jenkinsfile”, or “Docker registry”.  
  *Priority*: **Low**.  

- **MLOps Platforms**: CV lists MLflow, Kubeflow or Airflow for pipelines.  
  *Why*: Indicates familiarity with end-to-end model operations【11†L279-L282】.  
  *How*: Keywords “MLflow”, “Kubeflow”, “Airflow” in skills or project tools.  
  *Priority*: **Low**.  

- **Monitoring & Logging**: CV shows awareness of monitoring deployed models (e.g., Prometheus, Grafana).  
  *Why*: Ensuring model performance in production is a key MLOps skill.  
  *How*: “Prometheus”, “Grafana”, “model drift monitoring” in experience or skills.  
  *Priority*: **Low**.  

- **Container Registries**: CV mentions pushing images to Docker Hub or ECR.  
  *Why*: Part of deployment workflow; signals real-world deployment familiarity.  
  *How*: Look for “Docker Hub”, “AWS ECR”, or “Azure Container Registry”.  
  *Priority*: **Low**.  

- **Configuration Management**: CV lists tools like Ansible or Terraform.  
  *Why*: Shows knowledge of infrastructure as code, though more DevOps than core.  
  *How*: “Ansible”, “Terraform” under skills.  
  *Priority*: **Low**.  

- **Data Security/Privacy**: CV indicates awareness of security (GDPR, data encryption).  
  *Why*: Important for enterprise AI (though not specified in posting).  
  *How*: Terms like “encryption”, “GDPR”, “HIPAA” in context of data handling.  
  *Priority*: **Low**.  

## Mathematics / Statistics  

- **Linear Algebra**: CV lists courses or projects involving matrices, vectors, eigenvalues.  
  *Why*: Core of ML (e.g. neural networks use matrix math)【11†L203-L211】.  
  *How*: Coursework like “Linear Algebra”, or terms “matrix”, “vector”, “eigenvalue” in skills.  
  *Priority*: **High**.  

- **Calculus & Optimization**: CV shows understanding of derivatives, gradients.  
  *Why*: Crucial for training models (e.g. backpropagation).  
  *How*: “Calculus”, “derivative”, “gradient descent”, “Lagrange multipliers” listed.  
  *Priority*: **Medium**.  

- **Probability & Statistics**: CV references probability, distributions, hypothesis testing.  
  *Why*: Foundation for ML (uncertainty modeling)【11†L213-L216】【15†L340-L349】.  
  *How*: Coursework or terms like “probability”, “statistical inference”, “t-test”, “normal distribution”.  
  *Priority*: **High**.  

- **Statistical Modeling**: CV lists regression or Bayesian methods.  
  *Why*: Indicative of deeper stats knowledge (important in ML).  
  *How*: “Bayesian”, “linear regression”, “logistic regression” under skills.  
  *Priority*: **Medium**.  

- **Discrete Mathematics/Logic**: CV shows knowledge of logic, sets, graphs.  
  *Why*: Helpful in understanding algorithms and logic (not explicitly required, but beneficial)【11†L218-L221】.  
  *How*: Mention of “graph theory”, “set theory”, “logic” in coursework or skills.  
  *Priority*: **Low**.  

- **Regression Analysis**: CV mentions statistical regression analysis.  
  *Why*: Bridges statistics and ML.  
  *How*: “Linear regression”, “multivariate regression” in coursework or projects.  
  *Priority*: **Medium**.  

- **Hypothesis Testing**: CV references test types (t-test, chi-square).  
  *Why*: Shows ability to validate assumptions in data science.  
  *How*: “t-test”, “chi-squared”, “ANOVA” in context of analysis projects.  
  *Priority*: **Low**.  

- **Optimization Techniques**: CV includes nonlinear optimization methods.  
  *Why*: Underpins algorithm tuning (e.g. gradient-based optimizers).  
  *How*: “gradient descent”, “convex optimization” mentioned.  
  *Priority*: **Low**.  

- **Stochastic Methods**: CV shows knowledge of random processes or Markov chains.  
  *Why*: Useful in advanced ML (e.g. reinforcement learning).  
  *How*: “Markov chain”, “Monte Carlo”, “random processes” in coursework.  
  *Priority*: **Low**.  

- **Mathematical Maturity**: CV indicates overall math background (e.g. “B.Tech in CS” as proxy).  
  *Why*: A strong math background supports learning ML concepts.  
  *How*: Degrees or courses in mathematics, or statements like “advanced math”.  
  *Priority*: **Low**.  

## Code Quality / Testing  

- **Unit Test Frameworks**: CV lists use of testing frameworks (pytest, unittest, JUnit).  
  *Why*: Indicates commitment to reliability. Unit tests catch bugs early.  
  *How*: “pytest”, “unittest”, “TestNG” etc. under skills or project descriptions.  
  *Priority*: **Medium**.  

- **Code Reviews/Collaboration**: CV mentions participating in code reviews or pair programming.  
  *Why*: Reflects team-oriented, quality-focused development.  
  *How*: Phrases like “peer review”, “GitHub Pull Requests”, “collaborative coding”.  
  *Priority*: **Low**.  

- **Linting and Static Analysis**: CV shows familiarity with tools like flake8, pylint.  
  *Why*: Demonstrates attention to code style and error reduction.  
  *How*: “flake8”, “pylint”, “mypy” in skills.  
  *Priority*: **Low**.  

- **Documentation Practices**: CV indicates use of docstrings or Sphinx for docs.  
  *Why*: Good documentation is a hallmark of professional code.  
  *How*: “docstrings”, “README”, “Sphinx”, or evidence of well-commented code on GitHub.  
  *Priority*: **Low**.  

- **Reproducible Environments**: CV mentions Dockerfiles or `requirements.txt`.  
  *Why*: Ensures others can replicate results. Important for any ML experiment.  
  *How*: “Docker”, “requirements.txt”, “environment.yml” in project details.  
  *Priority*: **Medium**.  

- **Versioned Code**: CV shows disciplined use of version control beyond basics (e.g. branching strategies).  
  *Why*: Suggests mature development process.  
  *How*: “Git branching”, “Git workflow”, “release management”.  
  *Priority*: **Low**.  

- **Modular Code Design**: CV suggests writing reusable modules/functions.  
  *Why*: Clean architecture implies better maintenance.  
  *How*: Look for terms “modular”, “package”, or mention of object-oriented design principles.  
  *Priority*: **Low**.  

- **Continuous Integration**: CV indicates using CI/CD for testing code.  
  *Why*: Automating tests maintains code health.  
  *How*: “GitHub Actions”, “Travis CI”, “CircleCI” mentioned.  
  *Priority*: **Low**.  

## Datasets / Domain Knowledge  

- **NLP Projects/Datasets**: CV shows work with text or NLP (e.g. sentiment analysis, language models).  
  *Why*: The role’s LLM focus makes NLP experience very relevant.  
  *How*: “NLP”, “sentiment analysis”, “text classification”, or dataset names like “IMDB reviews”, “news articles” mentioned.  
  *Priority*: **High**.  

- **Computer Vision Projects**: CV includes image analysis or CV tasks (e.g. object detection).  
  *Why*: Broadens expertise, common ML domain.  
  *How*: “computer vision”, “CNN”, “image classification”, datasets like “CIFAR”, “ImageNet”.  
  *Priority*: **Medium**.  

- **Kaggle/Benchmark Datasets**: CV references working with known datasets (e.g. MNIST, Titanic).  
  *Why*: Familiarity with standard datasets shows applied practice.  
  *How*: Dataset names (MNIST, Kaggle competitions data) in project descriptions.  
  *Priority*: **Low**.  

- **Domain-Specific Knowledge**: CV indicates industry domain (e.g. healthcare, finance) related to data projects.  
  *Why*: Domain knowledge can help tailor AI solutions.  
  *How*: Mentions like “financial modeling”, “medical imaging” in projects.  
  *Priority*: **Low**.  

- **Data Privacy Awareness**: CV mentions handling sensitive data securely (anonymization, encryption).  
  *Why*: Important for user data protection.  
  *How*: “anonymization”, “GDPR compliance” in project or skills context.  
  *Priority*: **Low**.  

- **Time-Series Experience**: CV shows working with sequential data (forecasting).  
  *Why*: Adds versatility (time-series is common in many applications).  
  *How*: “time series”, “forecasting”, “ARIMA”, “LSTM” keywords.  
  *Priority*: **Low**.  

- **Reinforcement Learning**: CV lists RL projects or coursework.  
  *Why*: Indicates advanced AI interest (though not in posting, it’s emerging).  
  *How*: “reinforcement learning”, “Q-learning”, “Gym”.  
  *Priority*: **Low**.  

## Certifications / Training  

- **Relevant Degree**: CV lists a degree in CS, Data Science, AI, etc.  
  *Why*: The posting requires (or prefers) a CS/related degree【8†L83-L85】. Educational background assures foundational knowledge.  
  *How*: Check “B.Sc Computer Science”, “B.Tech IT”, etc. under education.  
  *Priority*: **High**.  

- **AI/ML Certifications**: CV includes certifications (e.g. Coursera’s ML or AI Specialization).  
  *Why*: Formal courses/certificates demonstrate commitment and knowledge【11†L303-L309】.  
  *How*: Specific cert names or programs (“Andrew Ng’s Machine Learning”, “Microsoft AI Engineer Program”【11†L303-L309】).  
  *Priority*: **Medium**.  

- **Cloud Certifications**: CV shows AWS/GCP/Azure certifications (e.g. AWS Certified ML Specialty).  
  *Why*: Validates cloud ML deployment skills. The resume advice suggests including cloud certs【15†L285-L294】.  
  *How*: Certification titles (“AWS Certified ML Specialty”, “Google Professional ML Engineer”).  
  *Priority*: **Low**.  

- **Kaggle Badges/Certificates**: CV lists Kaggle course certificates (e.g. Python, Machine Learning).  
  *Why*: Indicates self-driven learning in data science.  
  *How*: Names of Kaggle courses or badges (“Python”, “Intro to ML”).  
  *Priority*: **Low**.  

- **Professional Workshops or Bootcamps**: CV mentions AI/DS bootcamps (e.g. Data Science bootcamp).  
  *Why*: Additional intensive training in the field.  
  *How*: Program names (“Data Science Bootcamp at X”, “AI Workshop by Y”).  
  *Priority*: **Low**.  

- **MOOC Projects**: CV lists projects from online courses (Coursera, edX, Udacity).  
  *Why*: Complements academic degree with practical skills.  
  *How*: Course projects mentioned (e.g. “Capstone project for Coursera AI course”).  
  *Priority*: **Low**.  

- **Continuous Learning Evidence**: CV suggests active learning (e.g. “ongoing Python course”, blog).  
  *Why*: Shows enthusiasm and adaptability in fast-changing AI field.  
  *How*: Phrases like “currently learning…”, or links to recent course work.  
  *Priority*: **Low**.  

## Screening Workflow  

```mermaid
flowchart LR
    A[Candidate Submits CV] --> B[Automated Screening<br/>(Apply Rules)]
    B --> C{Score ≥ Threshold?}
    C -- Yes --> D[Shortlisted Applicants]
    C -- No --> E[Application Rejected]
    D --> F[Technical Interview & Coding Test]
    F --> G[Final Selection]
```

This flowchart outlines the CV screening workflow: resumes are collected and parsed by an ATS that applies the above rules. Candidates meeting a scoring threshold (passing most high-priority checks) are shortlisted for interviews; others are screened out.  

**Legend**: AI = Artificial Intelligence; ML = Machine Learning; LLM = Large Language Model; RAG = Retrieval-Augmented Generation.  

## Rule Summary Table  

| ID  | Short Rule                                | Category                | Priority  |
|-----|-------------------------------------------|-------------------------|-----------|
| 1   | Python proficiency                        | Programming             | High      |
| 2   | Secondary languages (R, C++, Java, etc.)  | Programming             | Medium    |
| 3   | Data structures & algorithms knowledge    | Programming             | High      |
| 4   | Object-oriented programming (OOP)         | Programming             | High      |
| 5   | Algorithmic coding/hackathon experience   | Programming             | Medium    |
| 6   | Software projects and GitHub portfolio    | Programming             | High      |
| 7   | Clean code practices (PEP8, etc.)         | Programming             | Medium    |
| 8   | Version control (Git/GitHub)              | Programming             | High      |
| 9   | Unit testing experience                   | Programming             | Medium    |
| 10  | Command-line/scripting skills             | Programming             | Low       |
| 11  | Supervised learning concepts (class/reg)  | ML/Deep Learning       | High      |
| 12  | Unsupervised learning concepts (clustering)| ML/Deep Learning       | High      |
| 13  | ML algorithm knowledge (decision trees etc.) | ML/Deep Learning     | High      |
| 14  | Use of ML libraries (scikit-learn)        | ML/Deep Learning       | High      |
| 15  | Use of DL frameworks (TensorFlow/Keras)   | ML/Deep Learning       | High      |
| 16  | Use of DL frameworks (PyTorch)            | ML/Deep Learning       | High      |
| 17  | Neural network experience (CNN/RNN)       | ML/Deep Learning       | High      |
| 18  | Transformer/LLM knowledge (GPT, BERT)     | ML/Deep Learning       | High      |
| 19  | LangChain/LLM framework familiarity       | ML/Deep Learning       | Medium    |
| 20  | RAG pipelines & vector DB familiarity     | ML/Deep Learning       | Medium    |
| 21  | AI agentic workflow familiarity          | ML/Deep Learning       | Medium    |
| 22  | Generative model knowledge (GAN, etc.)    | ML/Deep Learning       | Medium    |
| 23  | Hyperparameter tuning experience          | ML/Deep Learning       | Medium    |
| 24  | End-to-end ML pipeline experience         | ML/Deep Learning       | Medium    |
| 25  | Kaggle/competition participation          | ML/Deep Learning       | Medium    |
| 26  | Specialized ML domains (NLP/CV)           | ML/Deep Learning       | Medium    |
| 27  | Core theory awareness (overfitting, bias) | ML/Deep Learning       | Low       |
| 28  | Data cleaning & preprocessing             | Data Engineering       | High      |
| 29  | Pandas/NumPy proficiency                  | Data Engineering       | High      |
| 30  | Database/SQL experience                   | Data Engineering       | Medium    |
| 31  | Data visualization (Matplotlib/Seaborn)   | Data Engineering       | Medium    |
| 32  | ETL/pipeline tools (Airflow, Kafka)       | Data Engineering       | Low       |
| 33  | Big Data tools (Spark/Hadoop)             | Data Engineering       | Low       |
| 34  | Handling missing data/outliers            | Data Engineering       | Low       |
| 35  | Jupyter/Colab notebook use                | Data Engineering       | Low       |
| 36  | Data versioning (DVC)                     | Data Engineering       | Low       |
| 37  | NoSQL experience (MongoDB, etc.)          | Data Engineering       | Low       |
| 38  | FastAPI/Flask knowledge                   | Tools/Platforms       | Medium    |
| 39  | Git/GitHub proficiency                    | Tools/Platforms       | High      |
| 40  | Docker/containerization                   | Tools/Platforms       | Medium    |
| 41  | Kubernetes/orchestration                  | Tools/Platforms       | Low       |
| 42  | Cloud platforms (AWS/GCP/Azure)           | Tools/Platforms       | Medium    |
| 43  | MLops tools (MLflow, Kubeflow)            | Tools/Platforms       | Low       |
| 44  | LangChain/LangGraph experience            | Tools/Platforms       | Medium    |
| 45  | Vector DB tools (Pinecone, Weaviate)      | Tools/Platforms       | Medium    |
| 46  | LLM APIs experience (OpenAI, Claude)      | Tools/Platforms       | High      |
| 47  | AI coding assistants (Copilot, etc.)      | Tools/Platforms       | Low       |
| 48  | CI/CD (Jenkins, GitHub Actions)           | Tools/Platforms       | Low       |
| 49  | Published AI/ML projects                  | Projects/Portfolio    | High      |
| 50  | GitHub or portfolio link                  | Projects/Portfolio    | High      |
| 51  | Kaggle profile or badges                  | Projects/Portfolio    | Medium    |
| 52  | Open-source contributions                 | Projects/Portfolio    | Medium    |
| 53  | Relevant academic projects                | Projects/Portfolio    | Medium    |
| 54  | Capstone or thesis with ML                | Projects/Portfolio    | Medium    |
| 55  | Hackathon/competition results             | Projects/Portfolio    | Low       |
| 56  | Freelance or consulting AI work           | Projects/Portfolio    | Low       |
| 57  | Public demos/blog (portfolio)             | Projects/Portfolio    | Low       |
| 58  | Prior AI/ML internship/work               | Projects/Portfolio    | Medium    |
| 59  | Classification metrics (acc, precision)   | Evaluation Metrics    | High      |
| 60  | Regression metrics (MSE, MAE)             | Evaluation Metrics    | Medium    |
| 61  | Validation techniques (cross-val)         | Evaluation Metrics    | Medium    |
| 62  | ROC-AUC, confusion matrix                 | Evaluation Metrics    | Medium    |
| 63  | Experiment tracking (MLflow, TensorBoard) | Evaluation Metrics    | Low       |
| 64  | Overfitting/underfitting awareness        | Evaluation Metrics    | Low       |
| 65  | Feature importance/selection              | Evaluation Metrics    | Low       |
| 66  | Quantified results (e.g. “+% improvement”) | Evaluation Metrics    | Low       |
| 67  | Specialized metrics (BLEU, IOU, etc.)     | Evaluation Metrics    | Low       |
| 68  | Statistical significance (p-values)       | Evaluation Metrics    | Low       |
| 69  | Docker deployment                         | Deployment/MLOps      | Medium    |
| 70  | Kubernetes deployment                     | Deployment/MLOps      | Low       |
| 71  | Model serving via API (FastAPI/Flask)     | Deployment/MLOps      | High      |
| 72  | Cloud model deployment (SageMaker, etc.)  | Deployment/MLOps      | Medium    |
| 73  | CI/CD for ML (GitHub Actions, Jenkins)    | Deployment/MLOps      | Low       |
| 74  | MLflow/Kubeflow usage                     | Deployment/MLOps      | Low       |
| 75  | Monitoring deployed models (Prometheus)   | Deployment/MLOps      | Low       |
| 76  | Container registry usage (ECR, DockerHub) | Deployment/MLOps      | Low       |
| 77  | Configuration management (Ansible)        | Deployment/MLOps      | Low       |
| 78  | Data security/privacy awareness           | Deployment/MLOps      | Low       |
| 79  | Linear algebra coursework                 | Mathematics/Statistics | High      |
| 80  | Calculus/optimization knowledge           | Mathematics/Statistics | Medium    |
| 81  | Probability theory coursework             | Mathematics/Statistics | High      |
| 82  | Statistics coursework (p, mean, var)      | Mathematics/Statistics | High      |
| 83  | Regression analysis background            | Mathematics/Statistics | Medium    |
| 84  | Hypothesis testing knowledge              | Mathematics/Statistics | Low       |
| 85  | Discrete math/logic understanding         | Mathematics/Statistics | Low       |
| 86  | Stochastic/Markov processes               | Mathematics/Statistics | Low       |
| 87  | Multivariable calculus                    | Mathematics/Statistics | Low       |
| 88  | Optimization algorithms                   | Mathematics/Statistics | Low       |
| 89  | Unit testing experience                   | Code Quality/Testing  | Medium    |
| 90  | Code review participation                 | Code Quality/Testing  | Low       |
| 91  | Linting/static analysis usage             | Code Quality/Testing  | Low       |
| 92  | Documentation practices                   | Code Quality/Testing  | Low       |
| 93  | Reproducible environment (Dockerfile)     | Code Quality/Testing  | Medium    |
| 94  | Modular code design                       | Code Quality/Testing  | Low       |
| 95  | Continuous integration experience         | Code Quality/Testing  | Low       |
| 96  | NLP domain experience                     | Datasets/Domain       | High      |
| 97  | CV domain experience                      | Datasets/Domain       | Medium    |
| 98  | Familiarity with benchmark datasets       | Datasets/Domain       | Low       |
| 99  | Time-series data experience               | Datasets/Domain       | Low       |
| 100 | Relevant degree (CS/AI)                   | Certifications/Training | High    |

**Sources**: Job posting at Crownstack/QuickLabs【8†L93-L100】【8†L62-L69】; domain sources including career guides【11†L263-L272】【15†L300-L309】【1†L142-L149】. Each rule is grounded in either the official requirements or widely accepted AI engineering standards.