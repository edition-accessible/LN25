---
layout: document
date:  2025-02-06
title: "Methodology and prototype of the French Signposting study (2021-2024)"
previous: ../pages/diffuser.html
titlePrev: Informer
draft: false
---
  
<p>From 2021 to 2024, EDRLab was funded by french ministry of culture to make a study on the subject of information about digital book accessibility by online bookshop in order to make publishers efforts visible and ensure that people will find the book fitting theirs needs.</p>
<p>The study happened in french context but because a reader can buy an ebook anywhere on the planet we extend our implication by monitoring projects in other national contexts and participate actively to the international standardisation efforts, mainly at W3C.</p>
<h2>Context</h2>
<p>Directive (EU) 2019/882 article 13.2:&nbsp;Service providers shall prepare the necessary information in accordance (…) and shall explain how the services meet the applicable accessibility requirements. The information shall be made available to the public in written and oral format, including in a manner which is accessible to persons with disabilities. Service providers shall keep that information for as long as the service is in operation.</p>
<p>Some online retailers already display information about digital book accessibility functions (<a href="https://nnels.ca/items/mirror-lake">NNELS</a>, <a href="https://www.epagine.fr/ebook/9782221256923-le-fils-du-pecheur-sacha-sperling/">ePagine</a>, <a href="https://catalogo.fondazionelia.org/content/mrs-march-la-moglie-dello-scrittore-9788830542082">LIA</a>, <a href="https://benetechaccessiblebooks.vitalsource.com/products/college-transfer-success-making-a-smooth-donna-d-housman-alyssa-b-v9781533938695">Vitalsource</a>, <a href="https://user-images.githubusercontent.com/90989/115377146-a268a000-a1cf-11eb-8ca1-656552d3230d.png">Cantook</a>, <a href="https://www.amazon.fr/Invisible-Voices-English-Danny-Wilson-ebook/dp/B00WGDDEJI/ref=sr_1_1?keywords=invisible+voices&amp;qid=1669298752&amp;qu=eyJxc2MiOiIxLjAyIiwicXNhIjoiMC4wMCIsInFzcCI6IjAuMDAifQ%3D%3D&amp;sr=8-1">Amazon</a>) in very different ways.</p>
<p>In september 2021 <a href="https://www.w3.org/community/publishingcg/">Publishing Community Group @W3C</a> proposed a recommendation on the subject (<a href="https://www.w3.org/2021/09/UX-Guide-metadata-1.0/principles/">Display Guide sept.2021</a>) and asked for feedbacks. Discussions are taking place on the <a href="https://github.com/w3c/publ-a11y/">Accessibility task force issue tracker</a>.</p>

<h2>Methodology</h2>
<p>Our goal was to provide online booksellers and national lending websites with tools that could help them to improve the quality of services to people with disabilities. Eventually, we could help those people to get a similar experience to everyone and so, get closer to an inclusive society. We paid attention to two main stakes:
    </p><ul>
        <li>usability defines as information put online to help the reader choose the book that fits their needs;</li>
        <li>feasibility defines as the level of transparency and intelligibility of provided information. </li>
    </ul>
<p></p>
<p>In practice, we created <a href="https://edition-accessible.github.io/signalement/en/livre1en.html">prototypes of book information pages as fully accessible HTML webpages</a>. We based those prototypes on the existing guide, proposed by the World Wide Web Consortium (W3C).</p>
<p>An invitation was sent to 70 selected persons all actors of the eBook ecosystem, including organisations representing peoples with disabilities (blind, visually impaired and dys), libraries serving persons with print disabilities and public libraries. 51 persons responded ( <a href="https://edition-accessible.github.io/signalement/projet/EDRLab-workshops-metadata-2021.html" title="EDRLab-workshops-metadata-2021.html">see the list of participants)</a>). They were asked to manipulate the prototypes and participate in two workshops to discuss and respond to the two following questions: 
    </p><ul>
        <li>is the provided information of use to help me choose a book that fits my needs? </li>
        <li>is this information present and reachable to be provided to users?</li>
    </ul>
<p></p>
<p>We used participants responses to make iterations on the prototypes until we reached a consensus. A restitution of this work was given to the participants in February 2022. The next step is practical implementation by bookselling platforms providers, expected by the end of 2023.</p>
<p>As participants of the workshops enlightened difficulties with the vocabulary translated from English, we opted for an extension of the project through a national survey. A working group was constituted to establish a survey limited to 6 identified informations. For each of them, 3 sentences where proposed. A use case description page with examples was built to help respondent understand the feature to describe. </p>
<p>The survey was submitted to users in different ways depending on the target audience:
    </p><ul>
        <li>a general public survey distributed by epagine.fr and leslibraires.fr to which 221 people responded;</li>
        <li>a survey targeted at the pilot readers of the Éole multimedia library (Valentin Haüy association) to which 56 people responded;</li>
        <li>an interview with a panel of 4 persons from the Fédération Française des Dys (FFDYS).</li>
    </ul>
<p></p>
<p>The results are publicly available since September 2022 on the project dedicated webpage (in French).</p> 
​<h2>Results and Discussion</h2>
<p>From the initial phase, a synthesis of participants reactions was established. It can be resumed as follows: 
    </p><ol>
        <li>the proposed wording is overspecialized and generates misunderstandings; </li>
        <li>the user experience should be more inclusive;</li>
        <li>recommendations about the filtering user experience should be detailed;</li>
        <li>important books characteristics are missing;</li>
        <li>no mapping from MARC available.</li>
</ol>
<p></p>
<p>Point 1 was addressed by an extension of the project to propose a localized wording as described in the Methodology.</p>
<p>Point 2 to 5 were detailed and used to trigger actions to the relevant actors: 
    </p><ul>
    <li>a <a href="../documents/EDRLab-Signalement_lettreW3C_EN.pdf">feedback paper sent to the W3C Publishing Working Group</a> that led to an ongoing complete rewriting of the User Experience Guide;</li>
    <li>recommendations to ÉDItEUR, responsible of ONIX metadata standards, and to the MARC committee that are considered for next releases;</li>
</ul>
<p></p> 
<p>The discussion and rewriting of the Display guide has started at W3C PCG A11Y with mains topics on <a href="https://github.com/w3c/publ-a11y/issues/136">organizing metadata</a>, <a href="https://github.com/w3c/publ-a11y/issues/137">adding important information</a> and <a href="https://github.com/w3c/publ-a11y/issues/138">precisions about conformity</a></p>
<p>In France the work has followed with the building of Use cases (<a href="https://edition-accessible.github.io/vocabulaire/posts/fonctions/">Cas d’usage (Français)</a>) and a national survey about understandable vocabulary (<a href="https://edition-accessible.github.io/vocabulaire/posts/enqueteJuin2022/">Enquêtes</a>), this allowed us to build a <a href="https://edition-accessible.github.io/signalement/prototypes/protoype2/livre1.html">Prototype 3</a>.</p>
<p>In 2023 we expect live experimentation’s by <em>ePagine</em> and <em>leslibraires.fr</em>. The experimental display is also actually implemented in <em>Thorium Reader</em> and <em>Aldiko Next</em>.</p>
<p>We’ve also seen a side effect on persons in charge of adding accessibility informations. Because describing possibilities to access the content of a book means describing features of this book, the redefinition as use cases allowed a much better understanding not only of accessibility metadata but also of the book as a digital object and real impacts of care provided and attentions taken in it’s conception and production. To consolidate this effect, we reused reading use cases to build a <a href="https://www.lina25.fr/ressources/metadonnes">Dictionary of Accessibility metadata (in french)</a>.</p>

<h2>Considerations for the futur</h2>
<p>Still, access to knowledge and culture in a digital world implies moving an entire ecosystem, never forgetting that the reader is part of it and needs understanding to take advantage of the features made accessible. Reading and manipulating born accessible eBooks still require strong competencies for peoples with print disabilities. Some of the participants to the vocabulary study discovered possibilities of visual adjustments or navigation at different levels including print page related position.</p>
<p>Use cases and localized vocabulary are a great step but they are still not sufficient to make reader’s practices easier to learn. Because assistive technologies are often the main mean of access for peoples with print disabilities, they might be a wonderful vehicle to promote state of the art in industry standards and order to empower users in the use of born accessible materials.</p>
