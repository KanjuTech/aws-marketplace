# KanjuTech Transcription and Diarization model
This repository contains usage instructions for the [KanjuTech Transcription and Diarization Model](https://aws.amazon.com/marketplace/pp/prodview-ngtdx4ayt4emo).

This solution provides speech-to-text AI for businesses that require data security and accurate speaker labeling.

The Stable version (1.15) supports 10 languages with human-level accuracy for real-life data. 

The Release Candidate version supports an additional 19 languages with lower and unstable quality.

## Product Highlights

KanjuTech's Transcription and Diarization Model ensures secure end-to-end recognition of multi-participant conversations. The model efficiently handles over 12 hours of recording in just one hour on ml.p3.2xlarge.

### Data Security

This solution operates within Amazon SageMaker, securely within your AWS account. Per AWS security policy, SageMaker deploys images in an environment devoid of network or AWS service endpoint access. This means that when you launch this product from AWS Marketplace, this model is deployed without network access. Additionally, AWS restricts the model from accessing the internet during runtime. Therefore, when you use this product, only you can access your data. For more detailed information about security and data access, please refer to the following resources [here](https://docs.aws.amazon.com/marketplace/latest/userguide/ml-security-and-intellectual-property.html) and [here](https://docs.aws.amazon.com/marketplace/latest/buyerguide/product-types-machine-learning-products.html).

Delivery method via SageMaker supports compliance certifications:
C5, CCCS, CISPE, DESC CSP, DoD CC SRG, ENS High, FedRAMP, FINMA, GSMA, HIPAA BAA, HITRUST CSF, IAR, IRAP, ISMAP, ISO and CSA STAR certificates, K-ISMS, MTCS, OSPAR, PCI, Pinakes, PiTuKri, SNI 27001, SOC. For further details, please visit this [page](https://aws.amazon.com/ru/compliance/services-in-scope/).

### Supported Languages

Use "auto" mode to automatically detect the language or specify the language code:
- English: "en"
- Spanish: "es"
- French: "fr"
- Portuguese: "pt"
- Russian: "ru"
- Indonesian: "id"
- German: "de"
- Japanese: "ja"
- Turkish: "tr"
- Italian: "it"

The Release Candidate version supports additional languages with lower and unstable quality:
- Chinese: "zh"
- Vietnamese: "vi"
- Tagalog: "tl"
- Korean: "ko"
- Thai: "th"
- Polish: "pl"
- Ukrainian: "uk"
- Dutch: "nl"
- Romanian: "ro"
- Hungarian: "hu"
- Greek: "el"
- Swedish: "sv"
- Czech: "cs"
- Bulgarian: "bg"
- Slovak: "sk"
- Croatian: "hr"
- Danish: "da"
- Finnish: "fi"
- Norwegian: "no"

### Diarization (speaker detection and labeling)

This solution detects and labels any number of speakers. Use "auto" mode to automatically identify the number of speakers or specify the exact number.

### Benchmarks

The Stable version of the model supports 10 languages with human-level accuracy WER 3-8% for real-life data.

The Confusion Error Rate (CER) for audio with 6+ speakers is 2.2%.

Processing 1 hour of audio requires 4 min 56 sec of computation on recommended instance ml.p3.2xlarge.

### Pricing

This solution offers a 14-day free trial. There will be no software charges, but AWS infrastructure charges still apply. Free Trials will automatically convert to a paid subscription upon expiration.

Utilizing the model on our recommended ml.p3.2xlarge instances reduces software and infrastructure costs to less than $0.7 per record hour.

### Data example

The audio example was taken from [CABank English CallHome Corpus](https://ca.talkbank.org/access/CallHome/eng.html).

### Contact us

If you have any questions about our product, feel free to email us at aws@kanju.tech or schedule a [meeting](https://calendly.com/kanjutech).
