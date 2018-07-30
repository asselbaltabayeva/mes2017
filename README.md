# mes2017

The file `Antuan_De_Sent-Ekzyuperi__Kishkentay_Khanzada_pdf.secondHalf.kaz-tagger.cg3.txt' was produced with
the following commands:

apertium-kaz$ cat ~/src/mes2017/Antuan_De_Sent-Ekzyuperi__Kishkentay_Khanzada_pdf.secondHalf.txt | apertium -d . kaz-tagger | cg-conv -al > ~/src/mes2017/Antuan_De_Sent-Ekzyuperi__Kishkentay_Khanzada_pdf.secondHalf.kaz-tagger.cg3.txt

And the file `Antuan_De_Sent-Ekzyuperi__Kishkentay_Khanzada_pdf.secondHalf.kaz-disam.cg3.txt' was produced with
the following commands:
 
cat ~/src/mes2017/Antuan_De_Sent-Ekzyuperi__Kishkentay_Khanzada_pdf.secondHalf.txt | apertium -d . kaz-morph | cg-conv -al | vislcg3 -t -g apertium-kaz.kaz.rlx kaz.rlx.bin > ~/src/mes2017/Antuan_De_Sent-Ekzyuperi__Kishkentay_Khanzada_pdf.secondHalf.kaz-disam.cg3.txt
