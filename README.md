# AI Ethics, Fairness, and Security - Assignment Summary

**University of Central Missouri**  
**Department of Computer Science & Cybersecurity**  
**Course**: CS5720 Neural Networks and Deep Learning  
**Student**: Nagabandi Shravya  
**Student ID**: 700757053  
**Assignment**: Ethics, Bias, and Security in AI (Ch. 12)  

---

## 1. Black-box API in Model Stealing
**Explanation**: A black-box API refers to a model that is accessible only through its inputs and outputs—users can submit queries but cannot view internal weights, architecture, or training data. In model stealing, adversaries exploit this interface by sending numerous inputs to the API and using the outputs to train a copycat model that mimics the original.

---

## 2. Challenges of Achieving AI Fairness
**Explanation**: AI fairness is difficult to fully achieve in a single system due to competing definitions of fairness (e.g., equal opportunity vs. demographic parity), social context variations, data imbalances, and unintended model biases. One model might be fair in one group but unfair in another, making universal fairness hard to enforce.

---

## 3. Real-World AI Harms
**Examples**:
1. **Job discrimination** – An AI resume screener might unfairly reject applicants from certain zip codes or schools.
2. **Surveillance bias** – Facial recognition systems have higher error rates for minorities, leading to false arrests or targeting.

---

## 4. GAN Architecture: Adversarial Process
**Explanation**: In GANs (Generative Adversarial Networks), two models—a Generator and a Discriminator—compete:
- **Generator** tries to create realistic fake data.
- **Discriminator** tries to distinguish real data from fake.
They improve through competition: the Generator learns to fool the Discriminator, while the Discriminator learns to better spot fakes.

**Diagram Summary**:
```
Real Data --------> Discriminator -------> Real/Fake
     ^                                   ^
     |                                   |
Generator <---- Noise Input              |
     |-----------------------------------|
```

---

## 5. Real-World AI Harm: Misinformation in Generative AI
**Example**: A language model generates convincing fake news about public health policies.

**Mitigation Strategies**:
1. **Content filtering**: Integrate fact-checking or moderation pipelines.
2. **Training data curation**: Limit training on unreliable or controversial sources.

---

## 6. Bias & Fairness Tools – Aequitas: False Negative Rate Parity
**Metric**: False Negative Rate Parity

**Measures**: Ensures that false negative rates are similar across groups (e.g., race, gender).

**Importance**: Critical in domains like healthcare or hiring, where missing a true positive can cause harm.

**Model Failure Example**: A loan approval system may unfairly reject qualified applicants from minority groups more often than others.

---

## Submission Info
- [ ] Source code and responses uploaded to GitHub.
- [ ] Video demonstration includes code walkthrough and explanation.
- [ ] README summarizes all 6 questions and responses.

**GitHub Repo Link**: *(Add your repo link here)*
**Video Link**: *(Add your video link here)*

---

Feel free to reach out if you need any additional files or formatting adjustments!

