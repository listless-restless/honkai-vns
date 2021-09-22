# Honkai VNs

Continuation of Chinese-to-English translation work of Honkai Impact VNs, from https://github.com/zklm/honkai-vns, in the form of edits to .xml files that can be loaded via zklm's scripts into the VN viewer.



## Standalone viewers

The standalone VN viewers made by zklm are available below:

- **Anti-Entropy:** https://zklm.github.io/honkai-vn-antientropy/ (Standalone)
- **Durandal:** https://zklm.github.io/honkai-vn-durandal/ (Standalone)
- **Seven Swords:** https://zklm.github.io/honkai-vn-sevenswords/ (Standalone)
  - Note: does not currently have UI settings that allow toggling between languages - so it is largely useless for translations. Perhaps someone with the relevant coding experience can look into enabling this.

### How to use - for readers

To use the latest translation for  **Anti-Entropy**: 

1. Go to https://zklm.github.io/honkai-vn-antientropy/ 
2. Top right gear icon 
3. Change Custom EN XML Source to https://raw.githubusercontent.com/listless-restless/honkai-vns/main/antientropy/en/xml/ for the latest final branch, or https://raw.githubusercontent.com/listless-restless/honkai-vns/test/antientropy/en/xml/ for listless-restless' active test branch.
4. Refresh


To use the latest translation for  **Durandal**:

1. Go to https://zklm.github.io/honkai-vn-durandal/
2. Top right gear icon 
3. Change Custom EN XML Source to https://raw.githubusercontent.com/soricfetita/honkai-vns/main/durandal/en/xml/
4. Refresh

### How to use - for translators

1. Create a fork of my  `main` branch.
2. Do your edits in the relevant .xml documents.

If you have any questions feel free to message delialala#8801 in discord or catch me in lore chat on the official Honkai discord server. I won't merge with listless-restless' repostitory just yet because we haven't finished working on the Durandal vn.


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
| 21-29    |delialala#8801 and Sacron#6623| Complete|
| 30-31    |                 | Untranslated, see [Arylin-Renata](https://github.com/Ayrlin-Renata/honkai-vns) for very early edits |
### Seven swords

Currently untranslated
