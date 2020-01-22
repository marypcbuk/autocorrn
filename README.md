# autocorrn
Kickstart using Office AutoCorrect for shortcuts when typing with this collection of abbreviations and corrections

## What is this?

The AutoCorrect feature in Microsoft Office includes built-in corrections for a numebr of common mis-spellings as well as abbreviations for typing some characters like the copyright symbol, but you can add your own corrections and abberviations. Over many years of taking notes and transcribing interview responses, I have added hundreds of shortcuts for long words or product names with odd capitalisation or word separation that I need to get right, and thousands of corrections for typos that I make when typing fast. I copy these from PC to PC every time I switch machines (you can read more about how I do that here (https://www.zdnet.com/article/office-365-tip-using-add-to-autocorrect-to-make-you-more-productive/), and thought they might be useful to other people. "corrn" is my abbreviation of "correction".

### Prerequisites

Microsoft Office (Windows version)
The AutoCorrect.zip backup macro from https://wordmvp.com/FAQs/Customization/ExportAutocorrect.htm

NOTE: AutoCorrect works in all Office applications including OneNote and you can add items to AutoCorrect manually (or remove them) in any Office applicaiton using the AutoCorrect dialog. AutoCorrect entries added in one Office application will be available in other Office applications as soon as you open that application (if it was open when you made the AutoCorrect addition, you have to close it. In early and more recent versions of Word you can also add corrections to AutoCorrect by clicking on a mis-spelled word and choosing Add to AutoCorrect from the context menu (this option was removed and then returned to Word). But the only way that I know of to import AutoCorrect entries in bulk is with a Word macro, so Autocorrn should still be useful to you even if you only use Excel, PowerPoint or Outlook but not Word itself.

WARNING: Office macros are often used to spread malware. You will probably need to enable macros to use the AutoCorrect macro and you should always be cautious about downloading and running macros.

### Installing
Download the Autocorrn .DOC file for your proofing language.

Run the AutoCorrect macro. Choose "Backup" and save your existing AutoCorrect settings.
**If you have entered your own AutoCorrect options and want to keep them** open the Autocorrn .DOC file and add them manually, in the correct alphabetical order. Save the .DOC file.

Run the AutoCorrect macro. Choose "Restore" and browse to the Autocorrn .DOC file. **This will replace all existing AutoCorrect options** but it includes the default Microsoft AutoCorrect options.

Word will open, showing the Autocorrn .DOC file and the window will probably flash repeatedly as the AutoCorrect options are added. When you create a new document, the Autocorrn shortcuts like "nw" for "network", "perf" for "performance" and "defn" for "definition" will work.

## Deployment
Office stores different AutoCorrect items for each proofing language installed. The UK English set of shortcuts and corrections is much larger but - assuming the spelling is the same - you can copy entries into another AutoCorrect backup to add them under another proofing langauge. (I plan to add many of the UK English shortcuts and corrections to the US English file.)

If you don't like a specific AutoCorrect, use Ctrl-Z to undo it 

## Abbreviation tips
A lot of the abbreviations are two letters: "sw" for software, "hw" for "hardware", "nw" for "network. There are plurals and verb forms like "nws" and "nws" for "networks" and "networking". Some are ambiguous: "fw" is "framework" so the abbrevation for "firewall" is "firew". I use an abbreviation style I developed at school for words ending in -ion and similar, where I just use -n and miss out many other letters, so "defn" for "definition", "fn" for "function", "orchn" for "orchestration", "sepn" for "separation" and of course "corrn" for "correction". Again, I combine these: "compat" becomes "comaptible" but "compaty" becomes "compatibility". Other abbreviations may be slang: "mobo" for "motherboard" and "convo" for "conversation". There is a preponderance of technical and IT terms. Most of the product name abbreviations are Microsoft-specific like "pbi" for "Power BI" but "k8" for "Kubernetes" saves a lot of time!  

## Contributing

TBD Please read [CONTRIBUTING.md] for details on our code of conduct, and the process for submitting pull requests. 
I don't plan to change any of the abbreviations I use: if you want to have "nw" corrected to "northwest", fork away!
Suggestions: I've only created AutoCorrect entries in UK and US English. If you have a set of AutoCorrect entries in another proofing language, why not add them to Autocorrn?

## Versioning

TBD

## Authors

* **Mary Branscombe** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to Dave Rado who wrote the AutoCorrect macro I've used for many years, and to @PurpleBooth whose helpful README template (https://gist.githubusercontent.com/PurpleBooth/109311bb0361f32d87a2/raw/8254b53ab8dcb18afc64287aaddd9e5b6059f880/README-Template.md) I used.

* It is my hope that one day AutoCorrect options will roam with you from PC to PC automatically the way custom dictionaries do. If anyone in the Office team finds Autocorrn useful, feel free to push for that!
