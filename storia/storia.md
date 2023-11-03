---
theme: default
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('assets/background.svg')
marp: true
footer: https://github.com/matteobaccan/CorsoWebDesign versione del %date% %time%
---

# Storia del WebDesign

Dalla creazione di Internet all'evoluzione di HTML

![bg right](assets/matteo-baccan.jpg)

<!-- _paginate: false -->
<!-- _footer: "" -->
<!-- style: "
img[alt~='center'] {
  display: block;
  margin: 0 auto;
}
" -->

---

## Di cosa parleremo

Storia di internet: come si è evoluta la rete e quali sono i vantaggi che ha portato

Evoluzione di HTML: come è nato e si è evoluto

<matteo@baccan.it> – <https://www.baccan.it>

---

## Internet History

Slide provenienti dalle slide del libro: “Computer Networking: a Top Down Approach”

<https://gaia.cs.umass.edu/kurose_ross/ppt.php>

---

## 1961-1972: Principi iniziali di commutazione di pacchetto (packet-switching)

1961: Kleinrock - la teoria delle code dimostra l'efficacia della commutazione di pacchetto
1964: Baran - commutazione di pacchetto nelle reti militari
1967: ARPAnet concepito dall'Advanced Research Projects Agency (ARPA)
1969: primo nodo ARPAnet operativo

1972:
Demo pubblica di ARPAnet
NCP (Network Control Protocol) primo protocollo host-host
Primo programma di posta elettronica
ARPAnet ha 15 nodi

---

## 1972-1980: Interconnessione, nuove reti proprietarie

1970: Rete satellitare ALOHAnet alle Hawaii
1974: Cerf e Kahn - architettura per l'interconnessione di reti
1976: Ethernet presso Xerox PARC
fine anni '70: architetture proprietarie: DECnet, SNA, XNA
1979: ARPAnet ha 200 nodi

Principi di interconnessione di Cerf e Kahn

```text
- minimalismo, autonomia - nessuna modifica interna richiesta per interconnettere le reti
- modello di servizio best-effort
- instradamento senza stato (stateless routing)
- controllo decentralizzato

definiscono l'architettura Internet odierna
```

---

## 1980-1990: new protocols, a proliferation of networks

1983: deployment of TCP/IP
1982: smtp e-mail protocol defined
1983: DNS defined for name-to-IP-address translation
1985: ftp protocol defined
1988: TCP congestion control
new national networks: CSnet, BITnet, NSFnet, Minitel
100,000 hosts connected to confederation of networks

---

## Internet nel 1991

![center width:700px](assets/nsfnet.png)

---

## 1990, 2000s: commercialization, the Web, new applications

early 1990s: ARPAnet decommissioned
1991: NSF lifts restrictions on commercial use of NSFnet (decommissioned, 1995)
early 1990s: Web
hypertext [Bush 1945, Nelson 1960’s]
HTML, HTTP: Berners-Lee
1994: Mosaic, later Netscape
late 1990s: commercialization of the Web
late 1990s – 2000s:
more killer apps: instant messaging, P2P file sharing
network security to forefront
est. 50 million host, 100 million+ users
backbone links running at Gbps

---

## 2005-present: scale, SDN, mobility, cloud

aggressive deployment of broadband home access (10-100’s Mbps)
2008: software-defined networking (SDN)
increasing ubiquity of high-speed wireless access: 4G/5G, WiFi
service providers (Google, FB, Microsoft) create their own networks
bypass commercial Internet to connect “close” to end user, providing “instantaneous” access to social media, search, video content, …
enterprises run their services in “cloud” (e.g., Amazon Web Services, Microsoft Azure)
rise of smartphones: more mobile than fixed devices on Internet (2017)
~18B devices attached to Internet (2017)

---

-- DIBATTITO --
## 2023 AI

A fine 2022, ma soprattutto a partire dal 2023, l'AI inizia ad entrare in modo importante all'interno della rete.
-- DIBATTITO --

---

## Evoluzione di HTML

Informazioni provenienti dalle specifiche ufficiali

<https://html.spec.whatwg.org>

---

For its first five years (1990-1995), HTML went through a number of revisions and experienced a number of extensions, primarily hosted first at CERN, and then at the IETF.

With the creation of the W3C, HTML's development changed venue again. A first abortive attempt at extending HTML in 1995 known as HTML 3.0 then made way to a more pragmatic approach known as HTML 3.2, which was completed in 1997. HTML4 quickly followed later that same year.

HTML - HyperText Markup Language
CERN - European Organization for Nuclear Research, Ginevra
IETF - Internet Engineering Task Force (pubblica RFC)
RFC - Request for Comments
W3C - World Wide Web Consortium

---

The following year, the W3C membership decided to stop evolving HTML and instead begin work on an XML-based equivalent, called XHTML. This effort started with a reformulation of HTML4 in XML, known as XHTML 1.0, which added no new features except the new serialization, and which was completed in 2000.

After XHTML 1.0, the W3C's focus turned to
making it easier for other working groups to extend XHTML, under the banner of XHTML Modularization. In parallel with this, the W3C also worked on a new language that was not compatible with the earlier HTML and XHTML languages, calling it XHTML2

XHTML - eXtensible HyperText Markup Language
XML  - eXtensible Markup Language

---

Around the time that HTML's evolution was stopped in 1998, parts of the API for HTML developed by browser vendors were specified and published under the name DOM Level 1 (in 1998) and DOM Level 2 Core and DOM Level 2 HTML (starting in 2000 and culminating in 2003). These efforts then petered out, with some DOM Level 3 specifications published in 2004
but the working group being closed before all the Level 3 drafts were completed

API -  Application programming interface
DOM - Document Object Model

---

In 2003, the publication of XForms, a technology which was positioned as the next generation of web forms, sparked a renewed interest in evolving HTML itself, rather than finding replacements for it. This interest was borne from the realization that XML's deployment as a web technology was limited to entirely new technologies (like RSS and later Atom), rather than as a replacement for existing deployed technologies (like HTML).

XFORMS  - Extensible Markup Language Forms
RSS - Really Simple Syndication

---

A proof of concept to show that it was possible to extend HTML4's forms to provide many of the features that XForms 1.0 introduced, without requiring browsers to implement rendering engines that were incompatible with existing HTML web pages, was the first result of this renewed interest. At this early stage, while the draft was already publicly available, and input
was already being solicited from all sources, the specification was only under Opera Software's copyright.

---

The idea that HTML's evolution should be reopened was tested at a W3C workshop in 2004, where some of the principles that underlie the HTML5 work (described below), as well as the aforementioned early draft proposal covering just forms-related features, were presented to the W3C jointly by Mozilla and Opera. The proposal was rejected on the grounds that the proposal conflicted with the previously chosen direction for the web's evolution; the W3C staff and membership voted to continue developing XML-based replacements instead

---

don't break the web

Shortly thereafter, Apple, Mozilla, and Opera jointly announced their intent to continue working on the effort under the umbrella of a new venue called the WHATWG. A public mailing list was created, and the draft was moved to the WHATWG site. The copyright was subsequently amended to be jointly owned by all three vendors, and to allow reuse of the specification

WHATWG - Web Hypertext Application Technology Working Group

---

The WHATWG was based on several core principles, in particular that technologies need to be backwards compatible, that specifications and implementations need to match even if this means changing the specification rather than the implementations, and that specifications need
to be detailed enough that implementations can achieve complete interoperability without reverse-engineering each other.

---

The latter requirement in particular required that the scope of the HTML5 specification include what had previously been specified in three separate documents: HTML4, XHTML1, and DOM2 HTML. It also meant including significantly more detail than had previously been considered the norm

---

In 2006, the W3C indicated an interest to participate in the development of HTML5 after all, and in 2007 formed a working group chartered to work with the WHATWG on the development of the HTML5 specification. Apple, Mozilla, and Opera allowed the W3C to publish the specification under the W3C copyright, while keeping a version with the less restrictive license on the WHATWG site.

---

For a number of years, both groups then worked together. In 2011, however, the groups came to the conclusion that they had different goals: the W3C wanted to publish a "finished" version of "HTML5", while the WHATWG wanted to continue working on a Living Standard for HTML, continuously maintaining the specification rather than freezing it in a state with known
problems, and adding new features as needed to evolve the platform.

In 2019, the WHATWG and W3C signed an agreement to collaborate on a single version of HTML going forward: this document.

Approfondimenti <https://it.wikipedia.org/wiki/HTML>

---

## Fonti usate per la creazione di queste slide

<https://aaronsim.notion.site/b4f5dd304d9a4683a70167b6cc4b94f1?v=6cc0bd8ce4f04f26ad088e44c910b167> : elenco di prodotti basati su AI
<https://gaia.cs.umass.edu/kurose_ross/ppt.php> : “Computer Networking: a Top Down Approach”
<https://html.spec.whatwg.org> : specifiche HTML

L'immagine di sfondo è stata generata con <https://app.haikei.app>

Ogni immagine inserita riporta la fonte

---

## Disclaimer

L'autore ha generato questo testo in parte con GPT-3, il modello di generazione del linguaggio su larga scala di OpenAI. Dopo aver generato la bozza della lingua, l'autore ha rivisto, modificato e rivisto la lingua a proprio piacimento e si assume la responsabilità  ultima del contenuto di questa pubblicazione.
