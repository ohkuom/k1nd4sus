---
layout: page
title: FAQ
permalink: /faq
---

<style>
ul.jekyllcodex_accordion {position: relative; margin: 1.4rem 0!important; border-bottom: 1px solid rgba(0,0,0,0.25); padding-bottom: 0;}
ul.jekyllcodex_accordion li {border-top: 1px solid rgba(0,0,0,0.25); list-style: none; margin-left: 0;}
ul.jekyllcodex_accordion li input {display: none;}
ul.jekyllcodex_accordion li label {display: block; cursor: pointer; padding: 0.75rem 2.4rem 0.75rem 0; margin: 0;}
ul.jekyllcodex_accordion li div {display: none; padding-bottom: 1.2rem;}
ul.jekyllcodex_accordion li input:checked + label {font-weight: bold;}
ul.jekyllcodex_accordion li input:checked + label + div {display: block;}
ul.jekyllcodex_accordion li label::before {content: "+"; font-weight: normal; font-size: 130%; line-height: 1.1rem; padding: 0; position: absolute; right: 0.5rem; transition: all 0.15s ease-in-out;}
ul.jekyllcodex_accordion li input:checked + label::before {transform: rotate(-45deg);}
</style>

<ul class="jekyllcodex_accordion">
    <li>
        <input id="accordion1" type="checkbox" checked/>
        <label for="accordion1"><h2>Come posso entrare in K!nd4SUS?</h2></label>
        <div>
            Per entrare in K!nd4SUS unisciti ai gruppi ufficiali.<br>
            Le comunicazioni avverranno attraverso il canale <a href="https://t.me/k1nd4susCTF">Telegram News</a>, mentre la chat è nel gruppo <a href="https://t.me/+Rej8qbbkONMxZTdk">Telegram</a>. <br>
            Su <a href="https://discord.gg/6GTSrewn8y">Discord</a> ci troviamo per le competizioni e il giovedì sera alle 21 per risolvere challenge, discutere e approfondire argomenti.
        </div>
    </li>
    <li>
        <input id="accordion2" type="checkbox"/>
        <label for="accordion2"><h2>Cos'è una CTF?</h2></label>
        <div>Le CTF (Capture the Flag) sono un tipo speciale di competizioni di sicurezza informatica. Ci sono tre tipi comuni di CTF: Jeopardy, Attack-Defence e miste.<br>Le CTF in stile Jeopardy presentano una serie di domande (challenge) in diverse categorie. Ad esempio, Web, Forensics, Crypto, Binary o altro. <br>Le squadre possono guadagnare punti per ogni challenge risolta, e il punteggio varia a seconda della sua difficoltà. Alla fine del tempo di gioco, la somma dei punti determina il vincitore della CTF. Un esempio famoso di questo tipo di CTF sono le qualifications per la Defcon CTF.<br>Le CTF in stile Attack-Defence sono un altro tipo di competizione. Ogni squadra ha una propria rete (o anche solo un host) con servizi vulnerabili. Ogni squadra ha tempo per correggere i propri servizi e sviluppare exploit. Successivamente, gli organizzatori collegano i partecipanti alla competizione e inizia il gioco! Si devono proteggere i propri servizi per guadagnare punti di difesa e nel mentre attaccare gli avversari per guadagnare punti di attacco.<br>Storicamente, questo è stato il primo tipo di CTF, e la DEF CON CTF è considerata una sorta di Coppa del Mondo di tutte le altre competizioni.<br>Le CTF toccano spesso molti altri aspetti della sicurezza informatica: cryptography, steganography, binary analysis, reverse engineering, mobile security e altri.<br><br>Cortesia di <a href="https://ctftime.org/ctf-wtf">CTFTime</a>.
        </div>
    </li>
    <li>
        <input id="accordion3" type="checkbox"/>
        <label for="accordion3"><h2>Cos'è CyberChallenge.IT e perché dovrei partecipare?</h2></label>
        <div><a href="https://cyberchallenge.it/">CyberChallenge.IT</a>, programma di formazione per i giovani talenti tra i 16 e i 24 anni, è la principale iniziativa italiana per identificare, attrarre, reclutare e collocare la prossima generazione di professionisti della sicurezza informatica. <br> Per partecipare non servono esperti di programmazione ma grande passione, impegno e curiosità nelle discipline scientifico-tecnologiche (scienza, tecnologia, ingegneria e matematica). Servono anche capacità logiche, di problem solving, di comunicazione e, soprattutto, tanta voglia di imparare.<br> Dal 2020 CyberChallenge.IT è stato riconosciuto dal Ministero dell'Istruzione come progetto per la valorizzazione delle eccellenze; attraverso questi progetti, il Ministero individua le iniziative e le modalità di riconoscimento dei livelli di eccellenza conseguiti dagli studenti della scuola secondaria di secondo grado. <br><br>Cortesia di <a href="https://cyberchallenge.it/rules">CyberChallenge.IT</a>.

</div>
    </li>
    <li>
        <input id="accordion4" type="checkbox"/>
        <label for="accordion4"><h2>Cos'è CyberCup e come posso partecipare?</h2></label>
        <div><a href="https://cybercup.it/">CyberCup</a> consiste in un torneo Capture The Flag, costituito da vari eventi selezionati tra le gare internazionali a disposizione. Al torneo potranno partecipare tutte le squadre (senza limiti al numero di partecipanti) che si iscriveranno, incluse quelle di nuova costituzione. <br>La competizione sarà caratterizzata da un ranking delle squadre, il punteggio dipende dalle performance ad ogni gara selezionata. <br>Gli eventi di CyberCup verranno accuratamente scelti in accordo alla qualità e al livello di difficoltà da un comitato tecnico. Avranno maggiore priorità le competizioni organizzate da università e da squadre CTF italiane. Gli eventi avranno una difficoltà bilanciata in modo da accogliere sia squadre con poca esperienza che quelle più preparate. <br><br>Se vuoi partecipare ti basta fare parte del team e presentarti nel nostro server Discord nei giorni di gara!<br><br>Cortesia di <a href="https://cybercup.it/">CyberCup</a>.
        </div>
    </li>
<li>
    <input id="accordion5" type="checkbox" />
    <label for="accordion5"><h2>Che risorse consigliate?</h2></label>
    <div>
        <p><strong>Challenge:</strong></p>
        <ul>
            <li><a href="https://training.olicyber.it/">Training Olicyber</a> - beginner friendly</li>
            <li><a href="https://picoctf.org/">PicoCTF</a> - beginner friendly</li>
            <li><a href="https://pwn.college/">PwnCollege</a> - software security</li>
            <li><a href="https://cryptohack.org/">Crypto hack</a> - crypto</li>
            <li><a href="https://www.crypto101.io/">Crypto 101</a> - crypto</li>
            <li><a href="https://cryptopals.com/">CryptoPals</a> - crypto avanzate</li>
            <li><a href="https://www.hackthebox.com/">HackTheBox</a> - VM vulnerabili</li>
        </ul>

<p><strong>Offensive Security:</strong></p>
        <ul>
            <li><a href="https://www.youtube.com/@HackerSploit">HackerSploit</a> - red team e penetration testing</li>
            <li><a href="https://www.youtube.com/@_JohnHammond">John Hammond</a> - red team e Penetration testing</li>
            <li><a href="https://www.youtube.com/@Tib3rius">Tib3rius</a> - web security</li>
            <li><a href="https://www.youtube.com/@BlackHillsInformationSecurity">Black Hills Information Security</a> - penetration testing</li>
            <li><a href="https://www.youtube.com/@TCMSecurityAcademy">TCM Security</a> - web security e penetration testing</li>
            <li><a href="https://www.youtube.com/@specterops">SpecterOps</a> - red team</li>
            <li><a href="https://www.youtube.com/@Lsecqt">Lsecqt</a> - red team</li>
            <li><a href="https://www.youtube.com/@C5pider">5pider</a> - sviluppo malware e C2</li>
            <li><a href="https://www.youtube.com/@CosmodiumCS">Cosmodium CyberSecurity</a> - sviluppo malware e C2</li>
            <li><a href="https://www.youtube.com/@crr0ww">Crow</a> - sviluppo malware</li>
            <li><a href="https://www.youtube.com/@gitgudsec">gitgudsec</a> - sviluppo malware</li>
            <li><a href="https://www.youtube.com/@DeviantOllam">DeviantOllam</a> - penetration testing fisico</li>
            <li><a href="https://www.youtube.com/@DavidProbinsky">David Probinsky</a> - penetration testing fisico</li>
        </ul>

<p><strong>Reverse engineering:</strong></p>
        <ul>
            <li><a href="https://www.youtube.com/@pwncollege">pwn.college</a></li>
            <li><a href="https://www.youtube.com/@OffByOneSecurity">Off By One Security</a></li>
            <li><a href="https://www.youtube.com/@GuidedHacking">GuidedHacking</a></li>
            <li><a href="https://www.youtube.com/@jstrosch">Josh Stroschein</a></li>
            <li><a href="https://www.youtube.com/@sonianuj">Anuj Soni</a></li>
            <li><a href="https://www.youtube.com/@cyberraiju">Jai Minton</a></li>
            <li><a href="https://www.youtube.com/@L0psec">L0psec Reversing</a></li>
            <li><a href="https://www.youtube.com/@MalwareAnalysisForHedgehogs">MalwareAnalysisForHedgehogs</a></li>
            <li><a href="https://www.youtube.com/@OALABS">OALabs</a></li>
            <li><a href="https://www.youtube.com/@Vector35">VECTOR35</a> - BinaryNinja</li>
            <li><a href="https://www.youtube.com/@objectiveseefoundation">Objective-See Foundation</a> - Mac</li>
            <li><a href="https://www.youtube.com/@malwarexology">Andrew Chase</a> - Mac</li>
        </ul>

<p><strong>News:</strong></p>
        <ul>
            <li><a href="https://www.youtube.com/@rev3rsesecurity">rev3rse security</a></li>
            <li><a href="https://0dayfans.com/">0dayFans</a> - exploit research</li>
            <li><a href="https://www.youtube.com/@MentalOutlaw">MentalOutlaw</a></li>
            <li><a href="https://www.youtube.com/lowlevellearning">Low Level</a></li>
            <li><a href="https://www.youtube.com/@hak5">Hak5</a></li>
        </ul>

<p><strong>Network:</strong></p>
        <ul>
            <li><a href="https://www.youtube.com/@JeremysITLab">Jeremy's IT Lab</a></li>
            <li><a href="https://www.youtube.com/@davidbombal">David Bombal</a></li>
            <li><a href="https://www.youtube.com/@NetworkChuck">NetworkChuck</a></li>
        </ul>

<p><strong>Conferenze:</strong></p>
        <ul>
            <li><a href="https://www.nohat.it/">NoHat</a> - hacking, Bergamo</li>
            <li><a href="https://linuxdaymilano.org/">Linux Day Milano</a> - linux, Milano</li>
            <li><a href="https://m0lecon.it/">m0leCon</a> - hacking, Torino</li>
            <li><a href="https://www.hackinbo.it/">HackInBo</a> - hacking, Bologna</li>
            <li><a href="https://romhack.io/">RomHack</a> - hacking, Roma</li>
            <li><a href="https://owasp.org/www-chapter-italy/">OWASP Italy Day</a> - sicurezza web</li>
        </ul>
    </div>
</li>
    <li>
        <input id="accordion6" type="checkbox" />
        <label for="accordion6"><h2>Come posso pubblicare sul blog?</h2></label>
        <div>
            Se hai degli articoli che vorresti pubblicare sul <a href="blog">blog</a>, contatta <a href="https://t.me/ohkuom">[kuom]</a>.
        </div>
    </li>
    <li>
        <input id="accordion7" type="checkbox" />
        <label for="accordion7"><h2>Esistono un regolamento o uno statuto?</h2></label>
        <div>
            Certamente, <a href="regolamento">regolamento</a> e <a href="statuto">statuto</a> si trovano nelle apposite pagine di questo sito.
        </div>
    </li>
    <li>
        <input id="accordion8" type="checkbox" />
        <label for="accordion8"><h2>Voglio proporre un evento/iniziativa/CTF, chi posso contattare?</h2></label>
        <div>
            Scrivi a un membro del consiglio direttivo o all'email del gruppo. Saremo noi a ricontattarti con maggiori istruzioni.<br>La pagina <a href="contatti">contatti</a> del nostro sito potrebbe esserti utile.
        </div>
    </li>
    <li>
        <input id="accordion9" type="checkbox" />
        <label for="accordion9"><h2>Voglio collaborare in un progetto, come faccio?</h2></label>
        <div>
            Tieni sempre d'occhio il <a href="https://t.me/k1nd4susCTF">canale delle news</a>. Ogni volta che un nuovo progetto inizia sarà pubblicato un messaggio. A quel punto basterà seguire le istruzioni.
        </div>
    </li>
    <li>
        <input id="accordion10" type="checkbox" />
        <label for="accordion10"><h2>Sto collaborando a un progetto ma non ho accesso a GitHub. Cosa posso fare?</h2></label>
        <div>
            Chiedi al responsabile del progetto in questione di darti l'accesso alla repository. L'accesso all'intera organizzazione è previsto solo per gli organizzatori e per membri particolarmente attivi sia nello sviluppo che nelle CTF.
        </div>
    </li>
    <li>
        <input id="accordion11" type="checkbox" />
        <label for="accordion11"><h2>Voglio proporre un evento/iniziativa/CTF, chi posso contattare?</h2></label>
        <div>
            Scrivi a un membro del consiglio direttivo o all'email del gruppo. Saremo noi a ricontattarti con maggiori istruzioni.<br>La pagina <a href="contatti">contatti</a> del nostro sito potrebbe esserti utile.
        </div>
    </li>

</ul>

[canale]: https://t.me/k1nd4susCTF
[gruppo]: https://t.me/+Rej8qbbkONMxZTdk
[discord]: https://discord.gg/6GTSrewn8y