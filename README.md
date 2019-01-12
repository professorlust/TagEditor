### TagEditor annotation tool

TagEditor is a desktop application (tested on _Windows 10, 64-bit_) designed to annotate text for training with spaCy library.<br/>
With TagEditor you can label **dependencies, parts of speech, Named entities and text categories**.

### Installation

Download and unpack(extract) [**TagEditorSFX.exe**](https://github.com/d5555/TagEditor/raw/master/TagEditorSFX.exe)<br/>
Launch shortcut TagEditor.exe <br/>

### Usage

![alt text](https://github.com/d5555/TagEditor/blob/master/pics/dep800.gif)

&nbsp; Insert your text or open a text file and press Start tagging. Select a tag in TAG SET pannel then select a word to assign the tag. Select a head tag to assign dependency if you are working in the Dependencies window .<br/>
&nbsp; Right-click on a word to edit, delete, insert word, merge or split sentences. 
To merge sentences right-click on the first word of sentence. It is checked as **Sentence start**. Uncheck it and the sentence will merge with the previous sentence. <br/>
&nbsp; To delete all newline characters and extra whitespaces in the text, select the tab **Words** and press **Remove Whitespaces**.<br/> 
Press button **Create DATA** to create data in "simple training style" or JSON.<br/>
**Save project** for future editing. **Load project** to continue where you left.

**How to use Text Categories**<br/>
&nbsp; Select the score in the TAG SET pannel - True or False(i.e 1.0 or 0.0) and select a category label. Go to the editor window and click on sentence. Category and score will be added. You can easily **switch the score True/False** by just clicking on the score label in editor window. Supports multiple, non-mutually exclusive labels.<br/>
Use check button **Assign/unassign all** to assign/unassign all labels to all sentences in one click. Then you can manually change True/False status of each label or delete a label in the editor window.
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/cats.png)
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/dep.png)
![alt text](https://raw.githubusercontent.com/GitDimma/Tag-Editor/master/pics/ner.png)
<!---**************
### Extended version
Need help, found a bug or you would like get the extended version? [**New issue**](https://github.com/d5555/TagEditor/issues/new) or contact us at gitprojects5@gmail.com
**************
gitprojects5@gmail.com 


[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/d5555)<br/>--->
