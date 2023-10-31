# Projektin aloitus

Huom! ohjeessa mainittu group_? on ryhmästä riippuen group_1, group_2, jne
<ol>
<li>Yksi ryhmän jäsenistä kloonaa opettajan luoman Repon ja tekee seuraavat toimet</li>
<ol>
<li>Luo branchin nimeltä <b>initialize</b> </li>
<li>Tekee kansion nimeltään <b>backend</b> </li>
<li>Suorittaa backend-kansiossa komennot 
<ul>
<li>npx express-generator --no-view</li>
<li>npm install mysql</li>
</ul>
</li>
<li>Luo Qt:lla Qt-Widget sovelluksen kansioon <b>group_?</b> ja antaa sille nimeksi <b>bank-automat</b>. Kääntää sovelluksen ja tarkistaa että build-kansio on ilmestynyt kansioon bank-automat</li>
<li>Luo kansion group_? juureen tiedoston nimeltään <b>.gitignore</b> ja kirjoittaa sinne rivit 
<pre>
backend/node_modules/
bank-automat/build/
bank-automat/*.user
<pre>
</li>
<li>commitoi initialize-branchin ja puskee sen GitHubiin</li>
<li>Tarkistaa, että node_modules- ja build- kansio eivät ole GitHubissa, eikä myöskään pro.user tiedosto</li>
<li>Tekee <b>pull requestin</b>, jossa pyytää yhdistämään initialize branchin mainiin </li>
</ol>
<li>Joku toinen ryhmästä tarkistaa vielä että .gitignoressa mainitut tiedostot eivät ole GitHubissa ja hyväksyy pull requestin ja tekee 'mergen'</li>
<li>Nyt kaikki kloonaavat repon ja se, joka sen loi antaa komennot 
<ul>
<li>git checkout main</li>
<li>git pull origin main</li>
</ul>
</li>
<li>Tämän jälkeen jokainen luo oman branchin ja voi ruveta koodaamaan</li>
</ol>

<b>Huom!</b> Kaikki Git komennot on annettava kansion group_? juuressa.