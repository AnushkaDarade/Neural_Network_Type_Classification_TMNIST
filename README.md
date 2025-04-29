Abstract:

I have used the TMNIST (MNIST Typography) dataset Glyphs a collection of over 500,000 MNIST-style images comprised of 2,990 different font styles and 1,812 distinct glyphs.

The csv file is as follows:

- Column headers in the first row are ['fontname', 'glyphname', 'label','1', '2',.....'784'].
- 'Acme-Regular' and 'ZillaSlab-Bold' are only a couple of the font file names in the 'font_name' column.
- The unicodedata name for the glyph, such as "LATIN CAPITAL LETTER A" and "DEVANAGARI LETTER AA," is found in the "glyph_name" column.
- The 'glyphname' column provides the names of both characters, joined together with a '+' symbol, for glyphs that are represented by more than one unicode character. For instance, "" has the glyphname "DEVANAGARI SIGN ANUSVARA + DEVANAGARI LETTER A"
- The "label" column includes letters like "," "E," or "." the 784 additional columns


Output:

Accuracy was 94.81% utilizing a CNN Model with 50 epochs and a batch size of 100. Additionally, by altering the CNN model's epoch and batch size and evaluating the results, the model's accuracy can be improved.
