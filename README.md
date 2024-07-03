# Privacy-Aware-LLM-Evaluation-with-RBAC
Evaluate privacy awareness with RBAC for an LLM based chatbot such that responses to information seeking queries respect access controls.

## Product Overview
The solution helps evaluate privacy awareness driven by RBAC of LLM based conversational AI systems. The system generates questions tailored to different user roles to test the chat system's performance for privacy awareness for these user roles.  It identifies if the LLM is aware or under-aware of the access controls for each role. Under-awareness indicates that the chat system can provide such information to a user even though the role doesn't permit access to that data point. The solution takes as input: the metadata of the backend database, the description of roles and row/column level access controls for these roles. Anthropic's Claude model is leveraged to process this information and a questionnaire with synthetic database is provided in the first step. The system to be evaluated is configured with the synthetic DB to run against the queries under different scenarios mentioned in the questionnaire. The results are fed back to the inference endpoint to get the final evaluation.

## Product Highlight 

* The solution is intended to evaluate privacy awareness of fine-tuned LLMs/any LLM chat workflow, generating role-specific questions and assessing performance for domain-specific tasks.
* The solution uses application information, table schema, and role details to generate privacy-related questions, aiding in evaluating the LLM's performance for each role separately.
* Mphasis DeepInsights is a cloud-based cognitive computing platform that offers data extraction & predictive analytics capabilities. Need Customized Deep learning and Machine Learning Solutions? Get in Touch!

## Amazon Marketplace Link
The product can be found [here](https://aws.amazon.com/marketplace/pp/prodview-bxoqfosmld5yo).
