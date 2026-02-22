### How this project works

We’re approaching this project in small, practical steps so it stays grounded in real‑world healthcare workflows rather than abstract theory.

1. **Clarifying PHI and HIPAA concepts**  
   We start by mapping out what counts as protected health information (PHI) in typical clinical and administrative datasets, and how HIPAA’s rules apply in AI‑driven contexts (e.g., model training, inference, and data sharing).

2. **Integrating PHI and de‑identification**  
   Using synthetic health records, we identify which fields are sensitive, then apply de‑identification techniques such as removing direct identifiers, generalising quasi‑identifiers, and exploring Safe Harbor vs Expert Determination style thinking.

3. **Designing and testing case scenarios**  
   We create concrete scenarios (for example, building a model for readmission risk or triage support) and walk through how PHI should be handled at each step: data ingestion, preprocessing, model training, evaluation, and deployment. Each scenario is used to stress‑test our assumptions about privacy, access control, and data minimisation.

4. **Towards automation with AI**  
   The next phase is to prototype AI‑assisted components that can help automate parts of this workflow, such as:  
   - flagging PHI fields that require de‑identification,  
   - suggesting appropriate transformations,  
   - generating documentation or risk‑awareness checklists for a given use case.  

By layering these steps, the project evolves from manual patterns and examples into reusable building blocks that can help teams design safer, more compliant AI systems in healthcare.


The entire process is detailed as posts on LinkedIn to have a wider reach to the professionals up-and-coming in the field and foster curiosity. The background logistics and exact steps taken will be documented in GitHub.

