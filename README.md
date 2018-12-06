-*update 12/4/2018 - Text Categories option was included,  small fixes. Read how to use text categories.*<br/>
## TagEditor
TagEditor is a desktop application (tested on Windows 10, 64-bit) designed to annotate text for training with spaCy library.

Download and unpack(extract) TagEditorSFX.exe <br/>
Launch shortcut TagEditor.exe<br/>
Insert your text and press Start tagging. 

&nbsp; Select a tag in TAG SET pannel then select a word to assign the tag. You can tag dependencies, parts of speech, Named entities and text categories.<br/>
&nbsp; Right-click on a word to edit, delete, insert word, merge or split sentences. 
To merge sentences right-click on the first word of sentence. It is checked as **Sentence start**. Uncheck it and the sentence will merge with the previous sentence. <br/>
&nbsp; To delete all newline characters and extra whitespaces in the text, select the tab **Words** and press **Remove Whitespaces**.<br/> 
Press button **Create DATA** to create data in "simple training style" or JSON.<br/>
**Save project** for future editing. **Load project** to continue where you left.

**How to use Text Categories**<br/>
&nbsp; Select the score in the TAG SET pannel - True or False(i.e 1.0 or 0.0) and select a category label. Go to the editor window and click on sentence. Category and score will be added. You can easily **switch the score True/False** by just clicking on the score label in editor window. Supports multiple, non-mutually exclusive labels. 
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/cats.png)
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/datpic1.png)

![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/dep.png)
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/ner.png)
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/datpic.png)

## Donation

If this project help you reduce time to develop, you can give me a cup of coffee :)
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](paypal.me/d5555)<br/>
