Medieinstitutet FED22M
Uppgift 3: CV med CSS

Jag har gjort en sida som är tänkt att visa upp vem jag är, min utbildning och mina web-projekt. 
Mitt cv har jag valt att göra som en pdf-fil och går att ladda ner via 'download' knappen till vänster.

Jag har använt mig av flexbox, % och 'rem' för att få sidan responsiv, navbaren har 'position sticky' för att fasta uppe i kanten av fönstret, navbaren 
krymper med när fönstret ändrar storlek och går över till två ikoner när man kommer ner till mobilvy. Ikonerna är inlänkade med hjälp av bootstrap.
Men hjälp av Javascript har jag gjort så de två knapparna visar/gömmer min info-sida och mina menylänkar. Då jag inte kan javascript har jag ändå fått knapparna att fungera, men jag hade velat att dom hade någon sorts fade-in, swipe-in effect, och att menyn med länkarna försvann när man tryckt på en länk.

Jag har försökt att använda mig av allt vi gått igenom under lektionerna. Sidan är skriven i semantisk html, där jag även har kommenterat koden löpande. 
Jag har bl.a. använt mig av div, section, span, olika h-taggar, ul-listor, img-taggar, form, meta, importerat typsnitt från googlefonts ikoner från bootstrap m.m.

Siden är också skriven i sass som komplierat och komprimerat den till css, jag har delat upp min stil-filer för att dom ska vara lätta att få en överblick på och inte bli för långa/stora.
Jag änvände @use istället för @import för jag läst på 'sass-lang documentation' att import skullle fasas ut under de kommande åren.
https://sass-lang.com/documentation/at-rules/import

Sidan är läsabar, logisk och fungerar bra utan cssen.

Jag använde mixin för att kunna ha samma stil på flera element och färgerna ligger som variabler för att enklare styra färgtemat.

Sidan har commitats och synkats till github löpande under arbetet, jag har valt att distribuera sidan via netlify för jag ville pröva denna tjänsten, förra uppgiften distribuerade jag med
github pages och en gratis webdomäntjänst.
Jag har även valt att skaffa en egen domän, ( jonasnilsson.dev ) som jag kopplat till netlify distributionen och jag testade även med netlify-forms funktionen, bifogar skärmdump på att det fungrar men jag valde att plocka bort funktionen då det skulle tillkomma en månadsavgift om det användes mer än 100 gånger.

Bilderna jag har på sidan är optimerade med hjälp av Gimp och en webbtjänst. 
Jag har även lagt till en favicon som jag skapade i Gimp och ännu en webbtjänst.

