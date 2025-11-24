# tapestry-case-study/
 Case-study
# Tapestry — Regulated Data Sharing Platform (Healthcare & Fintech)

## 1. Context
Tapestry is a multi-tenant platform designed to allow organizations in regulated industries (healthcare, fintech, edtech) to **share sensitive data securely** without violating compliance requirements. It enables structured and unstructured data exchange through strict RBAC, vault-level encryption, audit trails, and pattern-based access rules.

## 2. Problem
Healthcare and financial organizations cannot easily share partner data because of:
- compliance barriers (HIPAA, PHI/PII, regional regulations)  
- siloed systems  
- lack of visibility  
- different data formats  
- manual or insecure integrations  

This prevents collaboration, delays workflows, and creates significant operational risk.

## 3. My Role
**Director of Product & Customer Success at DatumSure**  
I led:
- Product strategy & roadmap  
- Multi-tenant architecture definition (Partner → Vault → Dataset structures)  
- Discovery with top healthcare and fintech clients  
- Prioritization of compliance-first AI use cases  
- Delivery execution across PM, Eng, QA, CS  
- Customer onboarding & ARR expansion

## 4. Solution Overview
Tapestry enables:
- Secure multi-source data access  
- Vault-based storage for each organization  
- Row-level and field-level permissioning  
- Schema and dataset interoperability  
- RAG-style AI access (governed by compliance filters)  
- Full audit trails & access logs  

### Architecture (high-level)
- Multi-tenant platform  
- Each partner has vaults  
- Dataset-level RBAC  
- Policy engine for “Who can request what”  
- API + UI layer  
- Compliance & audit module  
- AI Access Layer (optional RAG-based augmentation)

(See `/solution/architecture.md`)

## 5. Key Decisions & Trade-offs
- **Strict-permission RAG vs open vector access:** chose rules-first AI.  
- **Vault-level tenancy** over “soft” multi-tenancy for safety.  
- **Regional data residency** to support global clients.  
- **Schema registry** to unify structured + unstructured data.

## 6. Impact
- Enabled clients to validate regulated AI use cases safely  
- Accelerated partner onboarding by **~40%**  
- Helped secure **$2M+ in ARR pipeline**  
- Reduced integration time from months → weeks  
- Supported live POCs with healthcare partners

## 7. Demo Video
🎥 *Placeholder:*  
Upload or link your demo (YouTube / Vimeo / Resume link)

## 8. Next Steps
- Expand policy engine for attribute-based access  
- Add dataset lineage  
- Build partner-level analytics dashboards  
