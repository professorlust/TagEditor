-*update 12/3/2018 - Text Categories option was included,  small fixes. Read how to use text categories.*<br/>
## TagEditor
TagEditor is a desktop application (tested on Windows 10, 64-bit) designed to annotate text for training with spaCy library.

Download and unpack(extract) TagEditorSFX.exe <br/>
Launch shortcut TagEditor.exe<br/>
Insert your text and press Start tagging. 

  Select a tag in TAG SET pannel then select a word to assign the tag. Then select a head token if you work in the Dependencies tab. You can tag dependencies, parts of speech, Named entities and text categories.<br/>
Right-click on a word to edit, delete, insert word, merge or split sentences. 
  To merge sentences right-click on the first word of sentence. It is checked as **Sentence start**. Uncheck it and the sentence will merge with the previous sentence. <br/>
  To delete all whitespace symbols in the text, select tab **Words** and press **Remove Whitespaces**.<br/> 
Press button **Create DATA** to create data in "simple training style" or JSON.<br/>
**Save project** for future editing. **Load project** to continue where you left.

**How to use Text Categories**<br/>
Select the score in the TAG SET pannel - True or False(i.e 1.0 or 0.0) and select a category tag. Go to the editor window and click on sentence. Category and score will be added. You can easily switch the score True/False by just clicking on the score label in editor window. You can also select a new category in TAG SET pannel and click on the category label in editor window to reassign the category. Delete label by clicking on ❎. Supports multi-label classification. 
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/cats.png)
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/datpic1.png)

![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/dep.png)
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/ner.png)
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/datpic.png)
