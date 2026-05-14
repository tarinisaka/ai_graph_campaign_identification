# AI-Assisted Phishing Campaign Detection and Profiling

This repository contains the implementation and resources for our paper accepted in *ACM Transactions on Internet Technology*, Special Issue on Human-AI Collaboration in Security Operations Centres.

Phishing attacks are increasingly large-scale, sophisticated, and difficult for security teams to analyze manually. This project explores how artificial intelligence can support, rather than replace, human expertise in phishing mitigation.

We propose a hybrid pipeline with three main components:

1. **Feature Extraction**  
   Fine-tuned language models analyze phishing emails and extract contextual features.

2. **Campaign Detection**  
   Community detection algorithms cluster similar phishing emails into coordinated campaigns.

3. **Campaign Profiling**  
   The system generates comprehensive summaries of detected campaigns to help SOC teams respond more efficiently.

By grouping related phishing emails and producing campaign-level summaries, the framework helps security analysts identify threats, block related emails, and respond to affected users more quickly.

[1] T. Saka, K. Vaniea, and N. Kökciyan, “AI-Enhanced Email Security: A Novel Pipeline for Phishing Campaign Detection and Profiling,” ACM Transactions on Internet Technology, Special Issue on Human-AI Collaboration in Security Operations Centres, 2025, accepted for publication.
