# Honkai VNs

Continuation of Chinese-to-English translation work of Honkai Impact VNs, from https://github.com/zklm/honkai-vns, in the form of edits to .xml files that can be loaded via zklm's scripts into the VN viewer.



## Standalone viewers

The standalone VN viewers made by zklm are available below:

- **Anti-Entropy:** https://zklm.github.io/honkai-vn-antientropy/ (Standalone)
- **Durandal:** https://zklm.github.io/honkai-vn-durandal/ (Standalone)
- **Seven Swords:** https://zklm.github.io/honkai-vn-sevenswords/ (Standalone)
  - Note: does not currently have UI settings that allow toggling between languages - so it is largely useless for translations. Perhaps someone with the relevant coding experience can look into enabling this.

### How to use - for readers

To use the latest translation e.g. for  **Anti-Entropy**: 

1. Go to https://zklm.github.io/honkai-vn-antientropy/ 
2. Top right gear icon 
3. Change Custom EN XML Source to https://raw.githubusercontent.com/listless-restless/honkai-vns/main/antientropy/en/xml/ for the latest final branch, or https://raw.githubusercontent.com/listless-restless/honkai-vns/test/antientropy/en/xml/ for my own (listless-restless) active test branch.
4. Refresh

### How to use - for translators

1. Create a fork of my  `main` branch.
2. Do your edits in the relevant .xml documents.
3. Create a pull request, and I'll get to merging it when I have time.

I have created a separate fork from zklm's original branch, but will initiate pull requests to his `master` once I have received confirmation from zklm that his project is still active. As of time of updating this readme, I have yet to hear from him.

For now, everything will remain in this fork, and I will continue to merge edits from the `test`("active") branch with my own `master` ("final") branch.

Since this is, as far as I am aware, the only active fork for this project (with other child forks/branches from contributing translators), I would advise any future translators to fork and request pulls from here first.



### Known issues

- **Multi-line scrolling not available:** Multi-line scrolling in the dialog boxes is not working in the standalone VN viewers (e.g. https://zklm.github.io/honkai-vn-antientropy/) as it does in Mihoyo's original viewer (https://event.bh3.com/avgAntiEntropy/indexAntiEntropy.php). This is the case for both Chinese and translated text. I do not have experience in Javascript, nor do I have access to the code that allows loading of Mihoyo and custom resources into a standalone viewer. So I cannot remedy this.
    - **Temporary solution:** For now, people who want to read all the text should go to the "Log", or at least set font size in the settings to the smallest possible value.



## Translation attributions

(Updated with translation progress)

### Anti-Entropy

| Chapters | Translators                                                  | Progress                                                     |
| -------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1-12     | listless-restless                                            | Complete                                                     |
| 13-15    | listless-restless, based on previous work by Aiatar and zklm | Complete                                                     |
| 16       | [asterae](https://github.com/asterae/honkai-vns) and listless-restless, based on previous work by Aiatar and zklm | Complete                                                     |
| 17-26    | Aiatar and zklm                                              | Partial, in progress, being worked on [RaytheonThunder](https://github.com/RaytheonThunder/honkai-vns) and [asterae](https://github.com/asterae/honkai-vns) |

### Durandal


| Chapters | Translators     | Progress                                                     |
| -------- | --------------- | ------------------------------------------------------------ |
| 1-20     | Aiatar and zklm | Complete, but may require further edits                      |
| 21-31    |                 | Untranslated, see [Arylin-Renata](https://github.com/Ayrlin-Renata/honkai-vns) for very early edits |

### Seven swords

Currently untranslated



## Other miscellany

Please note that while I am of Asian background, I am not a native Mandarin speaker, nor am I 100% fluent in Chinese. All translation from my end was done with a healthy dose of Google Translate, mdbg.net, and what I could remember from Chinese School and TVB dramas. If there are any corrections/suggestions, please create an issue and I'll get to it when I can. Do note that you are also free to generate your own fork and create your own edits, provided full credit is given to all translators.

Personally, I am currently only working on the Anti-Entropy VN. However, other volunteers have started looking into the other VNs as well. I will upload what I have previously translated into each of the chapters of the Anti-Entropy VN (up to Chapter 12). If time and energy permits, and if there is public interest, I may also contribute to the remaining chapters and VNs, adding to the work already done so far.

