# Allocator Bookkeeping Repository for Dekeinfo (深德科)

## Allocator JSON Link
https://github.com/filecoin-project/Allocator-Registry/blob/main/Allocators/Dekeinfo.json  
*(Will be added immediately after governance approval – registry PR already submitted)*

## Short Description of Pathway  
Dekeinfo offers one of the strictest and most transparent Large Commons Pathways on Filecoin Plus. We specialize in high-quality, legally compliant, openly licensed public datasets (scientific, cultural heritage, open-source software mirrors, public research, etc.). Clients receive thorough pre-verification, detailed sampling reports, and guaranteed long-term retrieval monitoring. Ideal for serious public-interest projects that want maximum governance trust and zero risk of future revocation.

## Contact Info
- Company: 深德科 (Dekeinfo)  
- Website: https://dekeinfo.com  
- Email: likunyou@derkee.com  
- Slack (Filecoin #fil-plus channel): @dekeinfo  
- GitHub: MetazoaZ  
- Bookkeeping Repository: https://github.com/MetazoaZ/Dekeinfo-Bookkeeping  
- Organization multisig: f2ptkuua5og4pubgau3ucylnspct5cuutu2vds27a  
- Allocator address: f2ii4vteekhiho7t2njfjm6iy5u4hmxdh3unm4ahi


## Client Diligence
We exclusively serve genuine public-interest projects producing non-commercial Commons Data.

Verification process:
- Official government-issued ID or business registration documents of applicant
- Proof of ownership/control over the dataset (organizational authority, project leadership, or signed declaration under penalty of perjury)
- Public project website/GitHub/repository demonstrating long-term public commitment
- Signed Letter of Intent (LOI) declaring the data is fully public, openly licensed, non-commercial, and fully compliant with GDPR, PIPL, CCPA, and all applicable privacy laws

Sybil resistance:
- Manual review of all applications (no automated pathway)
- Cross-checking of identity against public records and project history
- Rejection of any application with anonymous/unclear ownership
- Maximum 1 active application per legal entity/individual at any time

All client diligence materials are published in the corresponding ticket folder in this repository for full governance auditability.

##  Data Diligence
We perform rigorous pre-allocation sampling and verification to ensure only legitimate public commons data receives DataCap.

Requirements for dataset eligibility:
- Fully public and retrievable by anyone (no authentication, no paywalls, no regional restrictions)
- Transparent, machine-readable metadata publicly available
- Open license (CC0, CC-BY, CC-BY-SA, Apache-2.0, MIT, etc.)
- Zero personal/private/restricted data
- Strict compliance with GDPR, PIPL, CCPA and all applicable laws

Pre-allocation sampling procedure (mandatory for every request ≥10 TiB):
- Sample minimum 5–10% of proposed CIDs
- Absolute minimum: 100 files OR 500 GiB (whichever is larger)
- Tools used: lassie, cid.contact, saturn, trustless gateway, and other open retrieval tools
- Manual verification that sampled content exactly matches declared public purpose
- Check for excessive duplication with existing on-chain deals (>30% overlap → rejection)
- Confirmation that metadata is publicly accessible and accurate

Full sampling reports with retrieval proofs are published in this repository before any DataCap is allocated.


## Allocation policy

1. Client & Dataset Eligibility  
   • Data must be non-commercial Commons Data  
   • Fully public, retrievable with transparent metadata  
   • Open license (CC0, CC-BY, CC-BY-SA, Apache-2.0, MIT, etc.)  
   • Compliant with GDPR, PIPL, CCPA and all applicable laws  
   Required proof:  
   - Official ID & ownership docs  
   - Public project links (GitHub/website)  
   - Signed Letter of Intent (LOI)

2. Pre-Allocation Sampling  
   • Sample 5-10% of proposed CIDs  
   • Min: 10 files OR 500 GiB (whichever is larger)  
   • Tools: lassie, cid.contact, Saturn, trustless gateways  
   Must confirm:  
   - Content matches declared public purpose  
   - No private/personal/restricted data  
   - No excessive duplication of existing deals (>30% overlap → rejection)  
   - Metadata publicly accessible

3. Post-Deal Compliance  
   • Deals only with LDN-approved SPs
   • CIDs must exactly match pre-verified list (zero tolerance for additions/substitutions)  
   • Continuous IPNI indexing monitoring  
   • Monthly retrieval tests on random samples → target RPA ≥0.90  
   • Immediate DataCap revocation on any violation (private data discovered, retrieval failure, license change, etc.)

4. Public Audit Records (maintained ≥3 years)  
   Repository: https://github.com/MetazoaZ/Dekeinfo-Bookkeeping  
   Each ticket folder contains:  
   - Complete application + signed declarations  
   - Full sampling report with retrieval proofs and screenshots  
   - On-chain deal logs and transaction hashes  
   - Complete correspondence and final decision rationale  
   - Post-deal monitoring reports (monthly retrieval results)

## Risk Mitigation Strategies
- No automated or rapid allocation – every request is manually reviewed  
- Strict LOI with legal declarations under penalty of perjury  
- Immediate revocation + public notification for any violation  
- Monthly active monitoring of all allocated datasets (automated + manual)  
- Deals restricted to well-established, LDN-approved SPs only  
- All decisions and evidence published in this public repository within 48 hours  
- Multisig allocation (2-of-3) with keys held by separate team members  
- Regular internal audits and preparation for governance spot-checks

## Dispute Resolutions
Internal disputes (between Dekeinfo and client):  
All correspondence is conducted in the public GitHub issue. If the client believes a rejection was incorrect, they may submit additional evidence in the same thread. Final decision is published with detailed rationale. No appeals beyond providing new evidence.

External disputes (with governance or other allocators):  
Dekeinfo will provide the complete public record from this repository. Every allocation has verifiable pre-sampling proofs, retrieval tests, and on-chain evidence. We commit to full cooperation with any governance investigation and will immediately comply with any revocation request backed by evidence.

## Compliance Audit Check
- Pre-allocation: mandatory sampling reports published before any DataCap is sent  
- Post-allocation: monthly retrieval tests published in the corresponding ticket folder  
- Ongoing monitoring: automated alerts for indexing failures or retrieval issues  
- All records structured for easy governance review (one folder per allocation, standardized naming)  
- Repository has datacap-bot installed and actively maintained  
- We proactively notify governance via #fil-plus-large-allocators if any allocated dataset falls below RPA 0.90 or shows compliance issues

Dekeinfo operates with maximum transparency and strict adherence to Filecoin Plus principles. We welcome governance audits at any time.
