# booklet-printing--stampa-libretto

# Printing a booklet
The program 
## printing-booklet--stampa-libretto.nn.html
is a javascript/html for generating the numbers sequence described in https://help.gnome.org/users/evince/stable/singlesided-npage.html.en

If you are printing a booklet (which will perhaps be bound or stapled in the middle of each page), select the type of printer you will be using for printing from the list below. Then select the number of printed pages your booklet will have. 

n-page booklet

n is a multiple of 4.

If the number of pages in your PDF document is not a multiple of 4, you should add the appropriate number of blank pages (1, 2 or 3) to make it a multiple of 4. To do so, you can:

    Create a blank PDF using LibreOffice Writer.

    Merge the blank pages with your PDF document using PDF-Shuffler placing the blank pages at the end.

To print:

    Click File ▸ Print.

    Choose the General tab.

    Under Range, choose Pages.
        Type the numbers of the pages in this order:
            n, 1, 2, n-1, n-2, 3, 4, n-3, n-4, 5, 6, n-5, n-6, 7, 8, n-7, n-8, 9, 10, n-9, n-10, 11, 12, n-11...
            ...until you have typed n-number of pages.

    Choose the Page Setup tab.

    Under Layout, in the Two-side menu, select One Sided.

    In the Pages per side menu, select 2.

    In the Page ordering menu, select Left to right.

    In the Only print menu, select Odd sheets.

    Click Print.

    When all the pages have printed, flip the pages over and place them back in the printer.

    Click File ▸ Print.

    Choose the Page Setup tab.

    In the Only print menu, select Even sheets.

    Click Print.

