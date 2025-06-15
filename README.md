# Climate Policy Agentic RAG (USA)

A Retrieval-Augmented Generation (RAG) system powered by a single agent that answers natural language questions about U.S. climate mitigation policies. It integrates indexed policy documents, structured metadata, and scraped EPA content to generate responses.

---

## What the Agent Does

- Answers questions about U.S. climate policies
- Searches indexed policy text and EPA pages
- Queries structured metadata from CSV using SQL
- Generates context-aware responses

---

## Data Sources

1. GCCMPD Climate Policy Dataset
2. EPA climate-related web pages:
    - https://www.epa.gov/climate-change 
    - https://www.epa.gov/statelocalenergy/state-climate-policy
    - https://www.epa.gov/ghgemissions
    - https://www.epa.gov/international-cooperation/climate-partnerships
    - https://www.epa.gov/climate-indicators
    - https://www.epa.gov/climate-adaptation
  
---

## Tool Integration

   - gccmpd-policy-index: indexed U.S. policies
   - EPA Climate Policies: indexed scraped EPA content
   - climate_policy_db: SQL tool for CSV metadata

---

## Example Queries
<img width="1430" alt="image" src="https://github.com/user-attachments/assets/c266caab-cbfd-4fb8-9433-a6ce2aeb5700" />

---

## Future improvemnets

  - **Multi-country Support**: Add dynamic ISO code filtering to support other countries beyond the U.S.
  - **Arabic Language Integration**: Expand to Arabic policies for bilingual query handling.
  - **Web UI Interface**: Build a simple frontend for non-technical users to try the system.
