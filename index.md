# **AbjadAuthorID**: Shared Task on Authorship Identification in Languages that use the Arabic Script (Multiclass Classification)

### Hosted with [AbjadNLP(2026)](https://wp.lancs.ac.uk/abjad/) at EACL 2026, Rabat, Morocco

## 1. Overview of the Shared Task
This shared task, **AbjadAuthorID**, focuses on a multiclass classification challenge aimed at identifying the author of a given text excerpt from **literature** across diverse periods.

The task specifically focuses on languages that utilize the **Arabic script**, including:
- **MSA**
- **Urdu**
- **Kurdish**

Authorship identification is a fundamental problem in Natural Language Processing (NLP) and computational linguistics, with applications ranging from digital humanities and literary analysis to forensic linguistics. This task seeks to advance the state-of-the-art in authorship attribution for low-resource and morphologically rich languages that share the Abjad writing system.

## 2. Motivation
The motivation for this shared task stems from the need to develop robust authorship identification models for languages beyond English and those using the Latin script. Languages like Arabic, Urdu, Persian, and Kurdish share a common script but exhibit distinct linguistic features.
- **Script Commonality**: Exploring how the shared Abjad script influences authorship attribution features.
- **Linguistic Diversity**: Addressing the challenges of different language families (Semitic, Indo-Iranian) using the same script.
- **Multiclass Classification**: Moving beyond binary authorship verification to the more challenging problem of distinguishing between many potential authors.

## 3. Data
The dataset for this shared task consists of text excerpts from a diverse set of authors in the target languages.
- **Languages**: MSA, Urdu, and Kurdish.
- **Domain**: **Literature** (Novels, Short Stories, Poems, etc.).
- **Periods**: Texts spanning different historical periods.

*Detailed statistics and download links will be provided upon registration.*

## 4. Task Description
Participants are invited to submit systems for the following task:

### Authorship Identification (Multiclass Classification)
- **Goal**: Given a text excerpt, predict the correct author from a closed set of candidate authors.
- **Input**: A text segment (e.g., a paragraph or page).
- **Output**: The ID or Name of the author.
- **Evaluation Metric**: Macro-F1 Score (primary), Accuracy (secondary).

## 5. Tentative Timeline
- **December 25, 2025**: Release of training data
- **january 10, 2026**: Release of test data
- **january 15, 2026**: End of evaluation cycle (test submissions close)
- **January 17, 2026**: Final results released
- **August 22, 2025**: Shared task papers due date
- **January 20, 2026**: Notification of acceptance
- **February 3, 2026**: Camera-ready versions due
- **March 24–29, 2026**:  Workshop Dates [TBD]

## 6. Organizers
- **Shadi Abudalfa**, King Fahd University of Petroleum & Minerals
- **Saad Ezzini**, King Fahd University of Petroleum & Minerals
- **Ahmed Abdelali**, HUMAIN
- **Mustafa Jarrar**, Hamad Bin Khalifa University / Birzeit University
- **Mo El-Haj**, VinUniversity / Lancaster University

## 7. Participation Guidelines
- Use the following link to access the datasets and evalaute the perfomance of your system/model:
https://www.codabench.org/competitions/12332
https://www.codabench.org/competitions/12333
https://www.codabench.org/competitions/12334
- For participation guidelines, please refer to [Participation Guidelines](guidelines.md).
- Comprehensive instructions for preparing and submitting your paper(s) are available at [Paper Submission Guidelines](PAPER.md).

## References
1. Stamatatos, E. "A survey of modern authorship attribution methods." *Journal of the American Society for information Science and Technology*, 60(3), 538-556, 2009.
2. Koppel, M., et al. "Computational methods in authorship attribution." *Journal of the American Society for information Science and Technology*, 60(1), 9-26, 2009.

---

### Logistics and Support
- **Website Hosting**: GitHub Pages
- **Submission System**: Codabench
- **Communication Channels**:
  - Slack workspace
  - Mailing list
  - GitHub repository
- **Regular updates and participant support**

### Stay Updated
- Official **GitHub Repository**: [Link to Repo]
- Join our [Slack community](https://join.slack.com/t/arabicnlp2025-oqe5144/shared_invite/zt-39zsj6k6o-LP09lFRhLNuuHzkyahNRxw)

### Announcements and Updates
- The final phase will begin on July 20, 2025 (UTC-12h) and will run for 5 days, ending on July 25, 2025 (UTC-12h). During this time, each team must submit their predictions on the test set (not the validation set) via the Codabench system. Only submissions made within this timeframe will be considered as official contributions when submitting your papers to the OpenReview system.
- The main content of your paper should not exceed 4 pages. There is no page limit on appendices and references; these sections are excluded from the 4-page limit.

### Anti-Harassment policy
We uphold the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/index.php?title=Anti-Harassment_Policy), and participants in this shared task are encouraged to reach out with any concerns or questions to any of the shared task organizers.
