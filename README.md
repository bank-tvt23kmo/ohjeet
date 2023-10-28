# Projektin aloitus

<ol>
<li>Yksi ryhmän jäsenistä kloonaa opettajan luoman Repon ja tekee seuraavat toimet</li>
<ol>
<li>Luo branchin nimeltä **initialize** </li>
<li>Tekee kansion nimeltään **backend** </li>
<li>Suoritta backend-kansiossa komennot 
<ul>
<li>npm init</li>
<li>npm install express</li>
</ul>
</li>
<li>Luo Qt:lla Qt-Widget sovelluksen ja antaa sille nimeksi **bank-automat**. Kääntää sovelluksen ja tarkistaa että build-kansio on ilmestynyt kansioon bank-automat</li>
<li>Luo kansion group_? juureen tiedoston nimeltään **.gitignore** ja kirjoittaa sinne rivit 
<pre>
backend/node_modules/
bank-automat/build/
bank-automat/*.user
<pre>
</li>
<li>commitoi initialize-branchin ja puskee sen GitHubiin</li>
<li>Tarkistaa, että node_modules- ja build- kansio eivät ole GitHubissa, eikä myöskään pro.user tiedosto</li>
<li>Tekee **pull requestin**, jossa pyytää yhdistämään initialize branchin mainiin </li>
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
