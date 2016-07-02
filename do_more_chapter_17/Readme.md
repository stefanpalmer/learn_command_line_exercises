
# Chapter 17: Finding files (find)

## Do More

### Unix: Get your find index card and add this to the description side: "find STARTDIR -name WILDCARD -print". Next time you drill make sure you can say that phrase so you remember how find is formatted.

    Stefans-MacBook-Pro:~ $ find STARTDIR -name WILDCARD -print

### You can put any directory where the . (dot) is. Try another directory to start your search there.

    Stefans-MacBook-Pro:~ $ find Desktop/ -name "*.docx" -print
    Desktop//Contrastive Analysis/3-TTK2kol-delovni komunikacii-1.docx
    Desktop//Contrastive Analysis/CAA.docx
    Desktop//Contrastive Analysis/contrastive A.docx
    Desktop//documentshm/3-TTK2kol-delovni komunikacii-2.docx
    Desktop//documentshm/Alexis Tsipras Open Letter- Translation (Stefan Palmer).docx
    Desktop//documentshm/Climate Change Progress- Translation (Stefan Palmer).docx
    Desktop//documentshm/Cover Letter- Translation (Stefan Palmer).docx
    Desktop//documentshm/CV.docx
    Desktop//documentshm/Judiciary and Fundamental Rights- Translation (Stefan Palmer).docx
    Desktop//documentshm/Komunikacii1-2009.docx
    Desktop//documentshm/Stefan Palmer- CV.docx
    Desktop//documentshm/Stefan Palmer-1.docx
    Desktop//documentshm/Trans-Pacific Partnership- Translation (Stefan Palmer).docx
    Desktop//Kk.docx
    Desktop//LRTHW.docx
    Desktop//Ruby on Rails blog.docx
    Desktop//Stefan Palmer- Academic Transcripts and Certificates/Saarland University- Letter of Recommendation .docx
    Desktop//Stefan Palmer- Academic Transcripts and Certificates/Stefan Palmer- Statement of Interest.docx
    Desktop//Vesna/Превод, Александра.docx

### Look for all the video files on your computer starting at the home drive and use the > to save the list to a file. Remember how you can do SOMECOMMAND > SOMEFILE.txt and it will write the output of SOMECOMMAND to the file SOMEFILE.txt?

    (master) Stefan
    Stefans-MacBook-Pro:~ $ find ~/ -name "*.mp4" -print > SOMEFiLE.txt
    
    
    
