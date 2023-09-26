# Chinese-Camouflage-Spam-dataset
In the context of the Chinese language, the availability of spam text datasets is currently relatively scarce. The Chinese Camouflaged Spam(CCS) dataset with spam and non-spam information obtained from different sources.  These real-world data sources aim to provide a more com- prehensive representation of the current spam landscape. 

### CCS dataset structure
It contains four domains in order: 
1.the original spam-related text, 
2.the corrected version of the original text, 
3.the binary label for spam and non-spam detection, 
4.the multi label for spam intention recognition(contains 17 categories in total).

There are 23,788 samples in total. After annotation, approximately 42% of the samples contained unintentional or deliberate typo substitution. The total number
of typos reached a high count of 77,606.

### Clarification
All sensitive data are processed and masked in the dataset. The rule of masking is dicussed as follows:
For sensitive user information such as phone numbers, QQ numbers, or WeChat IDs, a special marker [PHONE] is used to replace them in both the original text and the corrected results. Additionally, suspicious websites are marked with a special marker [URL] as well in the original text and the corrected results.
