# BooksSpinsRecognition

The 1st step is the labeling of images. The dataset is 5 images (the original has 25 images). 
img_folder = './SpinesOnly5'

gr_tr = [
- ['Janet Evanovich', 'Wicked Business', 'Bantam'],
- ['Light of hope', 'Robert Vaughan'],
- ['CASS', 'The HEIR', 'HARPER TEEN'],
- ['Once Upon a Time', 'J.Randy Jaraborelly', 'Warner Books'],
- ['Baum/Furstenberg, Denslow', 'The Wizard of oz', 'Weekly Reader Books']]

Inference off-the-shelf models on this dataset.

**iPhone OCR**: 
pred_iphone = [
- ['EVANOVICH', 'WICKED', 'BUSINESS', 'BANTAM'],
- ['Light of hope', 'ROBERT VAUGHAM'],
- ['$cheir', 'Harper', 'Teen'],
- ['Once Upon a Sime| 8.Band, Seraborelli', 'Warner'],
- ['Baum/Furstenberg/Denslow', 'The wizard of oz', 'Weekly readers Books']]

**Performance**: error rate (WER)

Total words 32 Predicted words  20 Percentage  0.625
Each word is splitted, in lowercase, not preserve order...

**Post-processing**
