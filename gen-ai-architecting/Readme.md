## Functional Requirements
Dracut Elementary School seeks to invest in their own infrastructure to ensure student privacy regarding personal data. They are considering alternatives to costly cloud-based solutions due to budget constraints and the need for localized operations.

The school plans to utilize donated hardware from the town of Dracut, Massachusetts, specifically tailored for a project involving up to 300 students in grades 3-6, all located within the same building. Professional Services will be engaged to design, implement, and facilitate knowledge transfer to the existing onsite IT staff.

## Assumptions
The school has collaborated with local teachers and parents and identified that available hardware from their Computer Department is sufficient to support Large Language Models (LLMs) for educational purposes without compromising security or efficiency. With a budget of $5,000 allocated for this initiative, the focus will be on leveraging professional services to enhance in-house IT capabilities.

The project will utilize open-source LLMs running on dedicated hardware with either Windows or WSL, ensuring these systems are both efficient and secure for educational applications.

## Data Strategy
Security is a top priority, with measures in place to ensure data integrity and confidentiality. The school recognizes the importance of restricting inappropriate content access by implementing controls that monitor and filter inputs based on predefined guidelines.

To protect student privacy and maintain operational efficiency, all inputs will be restricted based on defined safety parameters. There is no requirement for internet connectivity in this project, ensuring a fully contained environment suitable for educational purposes.

## Budget
The $5,000 budget is dedicated to professional services required for staff development and infrastructure enhancements. This includes training, software licensing, and the deployment of necessary hardware to ensure a seamless transition to localized IT operations.

For this project, one PC/server will suffice as the primary operational platform. Enhanced performance capabilities, such as the use of an RTX 3070 GPU with 8GB of RAM, are planned to optimize computational tasks related to LLMs or data processing.

## Key Considerations
The school emphasizes the importance of maintaining control over data flow to prevent unauthorized access or misuse. By focusing on localized IT infrastructure and leveraging professional services, they aim to create a secure and efficient environment tailored specifically to their needs.


## Technical Implemention
The project will leverage the Mistral model using Ollama on a Windows-based system with WSL2. The model will be fine-tuned for sentence structuring, with vector database retrieval to improve contextual accuracy.
